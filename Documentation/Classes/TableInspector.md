---
layout : default
title : TableInspector
parent : Classes
---
# TableInspector

## Description

🗨️ Parse 4D catalog.4DCatalog file and extract table metadata for documentation

## Table of Contents

### Functions

- [constructor() [constructor]](#constructor)
- [_parseCatalog()](#_parsecatalog)
- [_parseTableAttributes()](#_parsetableattributes)
- [_parseField()](#_parsefield)
- [_parseFieldExtra()](#_parsefieldextra)
- [_parsePrimaryKey()](#_parseprimarykey)
- [_parseIndex()](#_parseindex)
- [_parseRelation()](#_parserelation)
- [_getTypeName()](#_gettypename)
- [_getIndexTypeName()](#_getindextypename)
- [_getRelationStateName()](#_getrelationstatename)
- [_mergeExistingComments()](#_mergeexistingcomments)
- [toObject()](#toobject)
- [toJSON()](#tojson)
- [saveToFile()](#savetofile)

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($TableName : Text)
```

Parse 4D catalog.4DCatalog file and extract table metadata for documentation

---

### _parseCatalog {#_parsecatalog}


```4d
Function _parseCatalog
```

Parse the catalog.4DCatalog XML file to extract table information

---

### _parseTableAttributes {#_parsetableattributes}


```4d
Function _parseTableAttributes($Line : Text)
```

Extract UUID

---

### _parseField {#_parsefield}


```4d
Function _parseField($Line : Text) -> Object
```

Parse field from XML line

**Returns:** `Object`

---

### _parseFieldExtra {#_parsefieldextra}


```4d
Function _parseFieldExtra($Field : Object; $Line : Text)
```

Parse field_extra attributes

---

### _parsePrimaryKey {#_parseprimarykey}


```4d
Function _parsePrimaryKey($Line : Text)
```

Parse primary key

---

### _parseIndex {#_parseindex}


```4d
Function _parseIndex($Lines : Collection; $Line : Text)
```

Check if this index references our table

---

### _parseRelation {#_parserelation}


```4d
Function _parseRelation($Lines : Collection; $Line : Text)
```

Parse relation definition

---

### _getTypeName {#_gettypename}


```4d
Function _getTypeName($TypeCode : Text) -> Text
```

Get human-readable type name from type code

**Returns:** `Text`

---

### _getIndexTypeName {#_getindextypename}


```4d
Function _getIndexTypeName($TypeCode : Text) -> Text
```

Get human-readable index type name

**Returns:** `Text`

---

### _getRelationStateName {#_getrelationstatename}


```4d
Function _getRelationStateName($StateCode : Text) -> Text
```

Get human-readable relation state name

**Returns:** `Text`

---

### _mergeExistingComments {#_mergeexistingcomments}


```4d
Function _mergeExistingComments
```

Merge table comment

---

### toObject {#toobject}


```4d
Function toObject -> Object
```

Convert to object for JSON export

**Returns:** `Object`

---

### toJSON {#tojson}


```4d
Function toJSON -> Text
```

Convert to JSON string

**Returns:** `Text`

---

### saveToFile {#savetofile}


```4d
Function saveToFile
```

Save to JSON file

---

---

*Generated from TableInspector.4dm*
*Last updated: 2025-11-13T00:30:42.964Z*
