# ClassInspector

## Description

ClassInspector - Analyzes 4D class files and extracts comprehensive metadata
Usage: var $Inspector : cs.ClassInspector := cs.ClassInspector.new($File)

## Table of Contents

### Properties

- [ClassName](#classname)
- [SuperClass](#superclass)
- [ClassAutoComment](#classautocomment)
- [ClassManualComment](#classmanualcomment)
- [Properties](#properties)
- [Functions](#functions)
- [Source](#source)
- [OutputFolder](#outputfolder)
- [ExistingJSON](#existingjson)
- [Changes](#changes)

### Functions

- [constructor() [constructor]](#constructor)
- [_parse()](#_parse)
- [_extractInlineComment()](#_extractinlinecomment)
- [_removeInlineComment()](#_removeinlinecomment)
- [_extractParameterComments()](#_extractparametercomments)
- [_loadExistingJSON()](#_loadexistingjson)
- [_mergeExistingPropertyComment()](#_mergeexistingpropertycomment)
- [_mergeExistingClassComment()](#_mergeexistingclasscomment)
- [_mergeExistingFunctionComment()](#_mergeexistingfunctioncomment)
- [_mergeExistingParameterComment()](#_mergeexistingparametercomment)
- [_recordChange()](#_recordchange)
- [toObject()](#toobject)
- [toJSON()](#tojson)
- [saveToFile()](#savetofile)

---

## Properties

### ClassName {#classname}

**Type:** `Text`

ClassInspector - Analyzes 4D class files and extracts comprehensive metadata
Usage: var $Inspector : cs.ClassInspector := cs.ClassInspector.new($File)

---

### SuperClass {#superclass}

**Type:** `Text`

---

### ClassAutoComment {#classautocomment}

**Type:** `Text`

Comment extracted from top of class file

---

### ClassManualComment {#classmanualcomment}

**Type:** `Text`

User-entered class documentation

---

### Properties {#properties}

**Type:** `Collection`

Collection of property objects

---

### Functions {#functions}

**Type:** `Collection`

Collection of function objects

---

### Source {#source}

**Type:** `Text`

---

### OutputFolder {#outputfolder}

**Type:** `4D.Folder`

Folder for JSON output

---

### ExistingJSON {#existingjson}

**Type:** `Object`

Previously saved JSON for comment merging

---

### Changes {#changes}

**Type:** `Collection`

List of changes detected

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($File : 4D.File)
```

---

### _parse {#_parse}


```4d
Function _parse
```

Main parsing function - processes the entire class file

---

### _extractInlineComment {#_extractinlinecomment}


```4d
Function _extractInlineComment($Line : Text) -> Text
```

Extract inline comment from a line (everything after //)

**Returns:** `Text`

---

### _removeInlineComment {#_removeinlinecomment}


```4d
Function _removeInlineComment($Line : Text) -> Text
```

Remove inline comment from a line

**Returns:** `Text`

---

### _extractParameterComments {#_extractparametercomments}


```4d
Function _extractParameterComments($Lines : Collection; $FuncStartIdx : Integer) -> Object
```

Extract parameter comments from lines following function declaration

**Returns:** `Object`

---

### _loadExistingJSON {#_loadexistingjson}


```4d
Function _loadExistingJSON
```

Load existing JSON file to preserve comments

---

### _mergeExistingPropertyComment {#_mergeexistingpropertycomment}


```4d
Function _mergeExistingPropertyComment($Prop : Object)
```

Merge existing property comment if available

---

### _mergeExistingClassComment {#_mergeexistingclasscomment}


```4d
Function _mergeExistingClassComment
```

Merge existing class comment if available

---

### _mergeExistingFunctionComment {#_mergeexistingfunctioncomment}


```4d
Function _mergeExistingFunctionComment($Func : Object)
```

Merge existing function comment if available

---

### _mergeExistingParameterComment {#_mergeexistingparametercomment}


```4d
Function _mergeExistingParameterComment($Param : Object; $FunctionName : Text)
```

Merge existing parameter comment if available

---

### _recordChange {#_recordchange}


```4d
Function _recordChange($ChangeDescription : Text)
```

Record a change

---

### toObject {#toobject}


```4d
Function toObject -> Object
```

Export to JSON object

**Returns:** `Object`

---

### toJSON {#tojson}


```4d
Function toJSON -> Text
```

Export to JSON string

**Returns:** `Text`

---

### saveToFile {#savetofile}


```4d
Function saveToFile -> 4D.File
```

Save JSON to file in Documentation\json\Classes folder

**Returns:** `4D.File`

---

---

*Generated from ClassInspector.4dm*
*Last updated: 2025-11-12T17:17:31.403Z*
