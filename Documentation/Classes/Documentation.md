# Documentation

## Description

////////

## Table of Contents

### Properties

- [CompiledClassesObject](#compiledclassesobject)

### Functions

- [generateClassDocumentation()](#generateclassdocumentation)
- [getCompiledClassesObject()](#getcompiledclassesobject)
- [generateTableDocumentation()](#generatetabledocumentation)
- [generateAllClassJSON()](#generateallclassjson)
- [generateMarkdownFromJSON()](#generatemarkdownfromjson)
- [_generateMarkdownForClass()](#_generatemarkdownforclass)

---

## Properties

### CompiledClassesObject {#compiledclassesobject}

**Type:** `Object`

---

## Functions

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

---

*Generated from Documentation.4dm*
*Last updated: 2025-11-12T17:04:21.595Z*
