---
layout : default
title : Documentation
parent : Classes
---
# Documentation

## Description

🗨️ This.CompiledClassesObject:=This.getCompiledClassesObject($CompileCode)

## Table of Contents

### Properties

- [CompiledClassesObject](#compiledclassesobject)

### Functions

- [constructor() [constructor]](#constructor)
- [generateClassDocumentation()](#generateclassdocumentation)
- [getCompiledClassesObject()](#getcompiledclassesobject)
- [generateTableDocumentation()](#generatetabledocumentation)
- [generateAllClassJSON()](#generateallclassjson)
- [generateMarkdownFromJSON()](#generatemarkdownfromjson)
- [_generateMarkdownForClass()](#_generatemarkdownforclass)
- [generateAllTableJSON()](#generatealltablejson)
- [generateMarkdownFromTableJSON()](#generatemarkdownfromtablejson)
- [_generateMarkdownForTable()](#_generatemarkdownfortable)

---

## Properties

### CompiledClassesObject {#compiledclassesobject}

**Type:** `Object`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($CompileCode : Boolean)
```

This.generateClassDocumentation()

---

### generateClassDocumentation {#generateclassdocumentation}


```4d
Function generateClassDocumentation
```

---

### getCompiledClassesObject {#getcompiledclassesobject}


```4d
Function getCompiledClassesObject($CompileCode : Boolean) -> Object
```

**Returns:** `Object`

---

### generateTableDocumentation {#generatetabledocumentation}


```4d
Function generateTableDocumentation($DataClass : 4D.DataClass)
```

---

### generateAllClassJSON {#generateallclassjson}


```4d
Function generateAllClassJSON
```

Generate JSON files for all classes using ClassInspector

---

### generateMarkdownFromJSON {#generatemarkdownfromjson}


```4d
Function generateMarkdownFromJSON
```

Generate markdown documentation from JSON files

---

### _generateMarkdownForClass {#_generatemarkdownforclass}


```4d
Function _generateMarkdownForClass($ClassJSON : Object) -> Text
```

Helper function to generate markdown for a single class

**Returns:** `Text`

---

### generateAllTableJSON {#generatealltablejson}


```4d
Function generateAllTableJSON
```

Get all table names from the catalog

---

### generateMarkdownFromTableJSON {#generatemarkdownfromtablejson}


```4d
Function generateMarkdownFromTableJSON
```

Generate markdown documentation from table JSON files

---

### _generateMarkdownForTable {#_generatemarkdownfortable}


```4d
Function _generateMarkdownForTable($TableJSON : Object) -> Text
```

Helper function to generate markdown for a single table

**Returns:** `Text`

---

---

*Generated from Documentation.4dm*
*Last updated: 2025-11-13T00:30:41.213Z*
