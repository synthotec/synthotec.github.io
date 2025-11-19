---
layout : default
title : TableInspector
parent : Classes
---
# TableInspector [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/TableInspector.4dm)

📊 **Overview:** 1 Constructor | 14 Functions

## 📝 Description

🗨️ Parse 4D catalog.4DCatalog file and extract table metadata for documentation

🕐 *Last updated: 2025-11-14T16:53:01.518Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [_parseCatalog](#_parsecatalog)
    - [_parseTableAttributes](#_parsetableattributes) (1 param)
    - [_parseField](#_parsefield) (1 param) → `Object`
    - [_parseFieldExtra](#_parsefieldextra) (2 params)
    - [_parsePrimaryKey](#_parseprimarykey) (1 param)
    - [_parseIndex](#_parseindex) (2 params)
    - [_parseRelation](#_parserelation) (2 params)
    - [_getTypeName](#_gettypename) (1 param) → `Text`
    - [_getIndexTypeName](#_getindextypename) (1 param) → `Text`
    - [_getRelationStateName](#_getrelationstatename) (1 param) → `Text`
    - [_mergeExistingComments](#_mergeexistingcomments)
    - [toObject](#toobject) → `Object`
    - [toJSON](#tojson) → `Text`
    - [saveToFile](#savetofile)
---

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($TableName : Text)
```

Parse 4D catalog.4DCatalog file and extract table metadata for documentation

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TableName` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### _parseCatalog {#_parsecatalog}


```4d
Function _parseCatalog
```

Parse the catalog.4DCatalog XML file to extract table information

---

#### _parseTableAttributes {#_parsetableattributes}


```4d
Function _parseTableAttributes($Line : Text)
```

Extract UUID

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Line` | `Text` | - | - |

---

#### _parseField {#_parsefield}


```4d
Function _parseField($Line : Text) -> Object
```

Parse field from XML line

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Line` | `Text` | - | - |

**Returns:** `Object`

---

#### _parseFieldExtra {#_parsefieldextra}


```4d
Function _parseFieldExtra($Field : Object; $Line : Text)
```

Parse field_extra attributes

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Field` | `Object` | - | - |
| `$Line` | `Text` | - | - |

---

#### _parsePrimaryKey {#_parseprimarykey}


```4d
Function _parsePrimaryKey($Line : Text)
```

Parse primary key

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Line` | `Text` | - | - |

---

#### _parseIndex {#_parseindex}


```4d
Function _parseIndex($Lines : Collection; $Line : Text)
```

Check if this index references our table

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Lines` | `Collection` | - | - |
| `$Line` | `Text` | - | - |

---

#### _parseRelation {#_parserelation}


```4d
Function _parseRelation($Lines : Collection; $Line : Text)
```

Parse relation definition

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Lines` | `Collection` | - | - |
| `$Line` | `Text` | - | - |

---

#### _getTypeName {#_gettypename}


```4d
Function _getTypeName($TypeCode : Text) -> Text
```

Get human-readable type name from type code

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TypeCode` | `Text` | - | - |

**Returns:** `Text`

---

#### _getIndexTypeName {#_getindextypename}


```4d
Function _getIndexTypeName($TypeCode : Text) -> Text
```

Get human-readable index type name

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TypeCode` | `Text` | - | - |

**Returns:** `Text`

---

#### _getRelationStateName {#_getrelationstatename}


```4d
Function _getRelationStateName($StateCode : Text) -> Text
```

Get human-readable relation state name

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StateCode` | `Text` | - | - |

**Returns:** `Text`

---

#### _mergeExistingComments {#_mergeexistingcomments}


```4d
Function _mergeExistingComments
```

Merge table comment

---

#### toObject {#toobject}


```4d
Function toObject -> Object
```

Convert to object for JSON export

**Returns:** `Object`

---

#### toJSON {#tojson}


```4d
Function toJSON -> Text
```

Convert to JSON string

**Returns:** `Text`

---

#### saveToFile {#savetofile}


```4d
Function saveToFile
```

Save to JSON file

---

---

*Generated from TableInspector.4dm*
