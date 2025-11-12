# ClassInspector

## Overview
ClassInspector analyzes 4D class files and extracts comprehensive metadata including properties, functions, parameters, return types, and doc comments. The inspector now supports:

- **Inline comments** for properties and functions
- **Parameter documentation** with dedicated comment syntax
- **Change tracking** between versions
- **Comment preservation** from previous JSON exports
- **Automatic JSON output** to `Documentation/json/Classes/`

## Usage

```4d
var $File : 4D.File
$File:=File("/PACKAGE/Project/Sources/Classes/EntityMigration.4dm")

var $Inspector : cs.ClassInspector
$Inspector:=cs.ClassInspector.new($File)

// Access metadata
var $ClassName : Text
$ClassName:=$Inspector.ClassName  // "EntityMigration.4dm"

var $Properties : Collection
$Properties:=$Inspector.Properties  // Collection of property objects

var $Functions : Collection
$Functions:=$Inspector.Functions  // Collection of function objects

var $Changes : Collection
$Changes:=$Inspector.Changes  // Changes detected from previous version

// Save to JSON file
var $SavedFile : 4D.File
$SavedFile:=$Inspector.saveToFile()  // Saves to Documentation/json/Classes/{ClassName}.json
```

## Comment Extraction

### Inline Comments for Properties

Inline comments on property declarations are automatically captured:

```4d
property Title : Text  // The title of the item
property Count : Integer:=0  // Number of items in stock
```

### Class-Level Comments

Class documentation can be extracted from comments at the top of the file or after `Class extends`:

```4d
// EntityMigration - Manages migration of entities between datastores
// Handles linking, creation, and synchronization of records
Class extends BaseClass
```

Or inline:

```4d
Class extends BaseClass  // Manages entity migration between datastores
```

### Inline Comments for Functions

Comments on the function declaration line are captured:

```4d
Function calculateValue($Price : Real) : Real  // Returns total inventory value
```

### First-Line Comments for Functions

Comments on the line immediately after the function declaration are also captured:

```4d
Function processOrder($Quantity : Integer) : Boolean
	// Process a customer order and update inventory
	If (This.Count>=$Quantity)
		// ... implementation
	End if
End if
```

### Parameter Documentation

**Note**: Parameters do not have auto comments extracted from code. All parameter documentation must be entered manually in the JSON file.
End if
```

Each parameter comment follows the format: `// $ParamName: description`

## JSON Output Structure

The generated JSON file includes:
- `className` (Text): Name of the class
- `superClass` (Text): Parent class name (if extends is used)
- `classAutoComment` (Text): Comment extracted from top of file or after Class extends (refreshed each run)
- `classManualComment` (Text): User-entered class documentation (preserved between runs)
- `properties` (Collection): Array of property objects
- `functions` (Collection): Array of function objects
- `changes` (Collection): List of detected changes since last run
- `lastUpdated` (Text): Timestamp of last analysis

## Property Object Structure

Each property in the `Properties` collection contains:
- `name` (Text): Property name
- `type` (Text): "property"  
- `propertyType` (Text): The 4D type (e.g., "Text", "Collection", "4D.File")
- `hasDefault` (Boolean): Whether a default value is assigned
- `defaultValue` (Text): The default value expression (if any)
- `lineNumber` (Integer): Line number in the source file
- `autoComment` (Text): Comment extracted from code (refreshed each run)
- `manualComment` (Text): User-entered comment (preserved between runs)

Example:
```json
{
  "name": "LinkFunctionCancelled",
  "type": "property",
  "propertyType": "",
  "hasDefault": true,
  "defaultValue": "False",
  "lineNumber": 3,
  "autoComment": "Flag indicating user cancelled the link dialog",
  "manualComment": "Set to true when user clicks Cancel in link prompt"
}
```

## Function Object Structure

Each function in the `Functions` collection contains:
- `name` (Text): Function name
- `type` (Text): "function"
- `modifiers` (Collection): Array of modifiers like ["exposed"] or ["local"]
- `isGetter` (Boolean): True if this is a getter function
- `isSetter` (Boolean): True if this is a setter function
- `parameters` (Collection): Array of parameter objects
- `returnType` (Text): The return type (e.g., "4D.Entity", "Collection")
- `lineNumber` (Integer): Line number in the source file
- `autoComment` (Text): Comment extracted from code (refreshed each run)
- `manualComment` (Text): User-entered comment (preserved between runs)

Example:
```json
{
  "name": "sync",
  "type": "function",
  "modifiers": [],
  "isGetter": false,
  "isSetter": false,
  "parameters": [
    {
      "name": "$Entity",
      "paramType": "4D.Entity",
      "isOptional": false
    },
    {
      "name": "$PreventSync",
      "paramType": "Boolean",
      "isOptional": false
    }
  ],
  "returnType": "4D.Entity",
  "lineNumber": 41,
  "autoComment": "Synchronize local entity with remote entity",
  "manualComment": "This should be called after any changes to ensure data consistency"
}
```

## Parameter Object Structure

Each parameter contains:
- `name` (Text): Parameter name (including $ prefix)
- `paramType` (Text): The parameter type
- `isOptional` (Boolean): True if parameter is wrapped in { }
- `manualComment` (Text): User-entered comment (preserved between runs)

**Note**: Parameters only support manual comments. Auto comments are not extracted from code for parameters.

Example:
```json
{
  "name": "$Quantity",
  "paramType": "Integer",
  "isOptional": false,
  "manualComment": "Number of items to order. Must be greater than 0"
}
```

## Dual Comment System

ClassInspector maintains **two separate comment fields** for most elements:

### Auto Comments (`autoComment`)
- **Applies to**: Class, Properties, Functions
- **Not for**: Parameters (manual only)
- **Source**: Extracted from inline comments, doc blocks, or first-line comments in code
- **Refreshed**: Every time the class is analyzed
- **Purpose**: Keep documentation synchronized with code comments
- **Priority**: Inline > First-line > Doc block

### Manual Comments (`manualComment`)
- **Applies to**: Class, Properties, Functions, Parameters
- **Source**: Manually entered by users in the JSON file
- **Preserved**: Between all runs, never overwritten by ClassInspector
- **Purpose**: Add additional context, usage notes, warnings, or examples
- **Editing**: Edit the JSON file directly to add or modify

This dual system ensures:
- Code comments are always current (via `autoComment`)
- User documentation is never lost (via `manualComment`)
- Both types of information are available for documentation generation

## Change Tracking

When a class is analyzed, ClassInspector:

1. **Loads existing JSON** (if present) from `Documentation/json/Classes/{ClassName}.json`
2. **Compares** current code with previous version
3. **Detects changes**:
   - New properties/functions added
   - Property types or default values changed
   - Function return types or parameter counts changed
   - Comments updated
4. **Preserves comments** - if a comment exists in the previous JSON but not in the code, it's preserved
5. **Records changes** in the `changes` collection

Each change object contains:
- `description` (Text): Description of what changed
- `timestamp` (Text): When the change was detected

Example changes:
```json
{
  "changes": [
    {
      "description": "New function added: processOrder",
      "timestamp": "2025-11-12T10:30:45.123Z"
    },
    {
      "description": "Property type changed: Count (Text -> Integer)",
      "timestamp": "2025-11-12T10:30:45.123Z"
    }
  ]
}
```

## JSON Output

The JSON file is automatically saved to:
```
Documentation/json/Classes/{ClassName}.json
```

The folder is created automatically if it doesn't exist.

### Complete JSON Structure

```json
{
  "className": "EntityMigration.4dm",
  "superClass": "",
  "properties": [...],
  "functions": [...],
  "changes": [...],
  "lastUpdated": "2025-11-12T10:30:45.123Z"
}
```

## Features

### Multi-line Support
ClassInspector correctly handles function signatures that span multiple lines by balancing parentheses.

### Doc Comment Extraction
Comments immediately preceding a property or function declaration are captured and cleaned (removing // and /* */ markers).

### Getter/Setter Detection
Functions declared with `Function get` or `Function set` are flagged with `isGetter` or `isSetter`.

### Modifier Detection
Function modifiers like `exposed` and `local` are captured in the `modifiers` collection.

### Complete Type Information
- Property types and default values
- Function parameter types (including optional parameters)
- Function return types (both `->$Var : Type` and `: Type` syntax)

## JSON Export

Call `toJSON()` to export all extracted metadata as a formatted JSON string:

```4d
var $JSON : Text
$JSON:=$Inspector.toJSON()
TEXT TO DOCUMENT(Folder(fk desktop folder).file("MyClass.json").platformPath; $JSON)
```

## Example Output

For a class with properties and functions, the JSON output looks like:

```json
{
  "className": "EntityMigration.4dm",
  "superClass": "",
  "properties": [
    {
      "name": "_RemoteDataStore",
      "type": "property",
      "propertyType": "4D.DataStoreImplementation",
      "hasDefault": true,
      "defaultValue": "DataStore(2)",
      "lineNumber": 1,
      "docComment": ""
    }
  ],
  "functions": [
    {
      "name": "sync",
      "type": "function",
      "modifiers": [],
      "isGetter": false,
      "isSetter": false,
      "parameters": [...],
      "returnType": "4D.Entity",
      "lineNumber": 41,
      "docComment": ""
    }
  ]
}
```

## Helper Classes

The following helper classes are available for working with extracted metadata:

- `cs.ClassProperty`: Stores property metadata
- `cs.ClassFunction`: Stores function metadata
- `cs.ClassParameter`: Stores parameter metadata

Each has a `toObject()` method for JSON serialization.

## Notes

- The parser handles both `\r\n` and `\n` line endings
- Block comments (`/* */`) and single-line comments (`//`) are both supported
- The `Continue` keyword is used to skip to the next iteration in the parsing loop
- Properties and functions are stored in the order they appear in the source file
- LSP errors about "undeclared properties" are false positives and will clear when 4D refreshes its index

## Batch Processing

Process all classes in the Classes folder:

```4d
var $ClassesFolder : 4D.Folder
$ClassesFolder:=Folder("/PACKAGE/Project/Sources/Classes/"; fk platform path)

var $ClassFiles : Collection
$ClassFiles:=$ClassesFolder.files()

var $File : 4D.File
For each ($File; $ClassFiles)
	If ($File.extension=".4dm")
		var $Inspector : cs.ClassInspector
		$Inspector:=cs.ClassInspector.new($File)
		$Inspector.saveToFile()
		
		// Report changes
		If ($Inspector.Changes.length>0)
			TRACE
		End if 
	End if 
End for each
```

## Comment Preservation Example

**First run** (no existing JSON):
```4d
property Title : Text  // The title of the item
```
JSON output:
```json
{
  "name": "Title",
  "autoComment": "The title of the item",
  "manualComment": ""
}
```

**Second run** (comment removed from code, manual comment added to JSON):
```4d
property Title : Text
```
User edits JSON to add:
```json
{
  "name": "Title",
  "autoComment": "The title of the item",
  "manualComment": "Required field, must not be empty"
}
```

**Third run** (code comment changed):
```4d
property Title : Text  // Item title text
```
JSON output:
```json
{
  "name": "Title",
  "autoComment": "Item title text",
  "manualComment": "Required field, must not be empty"
}
```
Result: `autoComment` refreshed from code, `manualComment` preserved

**Fourth run** (all comments removed from code):
```4d
property Title : Text
```
JSON output:
```json
{
  "name": "Title",
  "autoComment": "",
  "manualComment": "Required field, must not be empty"
}
```
Result: `autoComment` cleared (no code comment), `manualComment` preserved

### Parameter Comment Preservation

Parameters also support the dual comment system:

**First run**:
```4d
Function sync($Entity : 4D.Entity; $PreventSync : Boolean) : 4D.Entity
	// $Entity: The entity to synchronize
	// $PreventSync: If true, prevents automatic sync
```
JSON output:
```json
{
  "name": "$Entity",
  "autoComment": "The entity to synchronize",
  "manualComment": ""
}
```

**Second run** (user adds manual comment):
User edits JSON:
```json
{
  "name": "$Entity",
  "autoComment": "The entity to synchronize",
  "manualComment": "Must have MigrationID property"
}
```

**Third run** (code comment changed):
```4d
Function sync($Entity : 4D.Entity; $PreventSync : Boolean) : 4D.Entity
	// $Entity: Local entity to sync with remote datastore
```
JSON output:
```json
{
  "name": "$Entity",
  "autoComment": "Local entity to sync with remote datastore",
  "manualComment": "Must have MigrationID property"
}
```
Result: `autoComment` updated from code, `manualComment` preserved

This dual-comment preservation works independently for:
- Property `autoComment` and `manualComment`
- Function `autoComment` and `manualComment`
- Parameter `autoComment` and `manualComment` (matched by function name and parameter name)
