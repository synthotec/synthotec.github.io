---
layout : default
title : Documentation
parent : Classes
---
# Documentation

📊 **Overview:** 1 Properties | 1 Constructor | 14 Functions

## 📝 Description

🗨️ This.CompiledClassesObject:=This.getCompiledClassesObject($CompileCode)

🕐 *Last updated: 2025-11-13T13:33:26.578Z*

---

## 📑 Table of Contents

### 📋 Properties (1)

- [CompiledClassesObject](#compiledclassesobject) : `Object`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (14):**

- [generateClassDocumentation](#generateclassdocumentation)
- [getCompiledClassesObject](#getcompiledclassesobject) (1 param) → `Object`
- [generateTableDocumentation](#generatetabledocumentation) (1 param)
- [generateAllClassJSON](#generateallclassjson)
- [generateMarkdownFromJSON](#generatemarkdownfromjson)
- [_generateMarkdownForClass](#_generatemarkdownforclass) (1 param) → `Text`
- [_generateFunctionMarkdown](#_generatefunctionmarkdown) (1 param) → `Text`
- [generateAllTableJSON](#generatealltablejson)
- [generateMarkdownFromTableJSON](#generatemarkdownfromtablejson)
- [_generateMarkdownForTable](#_generatemarkdownfortable) (1 param) → `Text`
- [generateAllFormJSON](#generateallformjson)
- [discoverRelationships](#discoverrelationships) → `Integer`
- [generateMarkdownFromFormJSON](#generatemarkdownfromformjson)
- [_generateMarkdownForForm](#_generatemarkdownforform) (1 param) → `Text`

### 🔗 Related Items

- [Classes](#-related-classes) (1)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `CompiledClassesObject` | `Object` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($CompileCode : Boolean)
```

This.generateClassDocumentation()

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CompileCode` | `Boolean` | - | - |

---

### ⚙️ Regular Functions

#### generateClassDocumentation {#generateclassdocumentation}


```4d
Function generateClassDocumentation
```

---

#### getCompiledClassesObject {#getcompiledclassesobject}


```4d
Function getCompiledClassesObject($CompileCode : Boolean) -> Object
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CompileCode` | `Boolean` | - | - |

**Returns:** `Object`

---

#### generateTableDocumentation {#generatetabledocumentation}


```4d
Function generateTableDocumentation($DataClass : 4D.DataClass)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DataClass` | `4D.DataClass` | - | - |

---

#### generateAllClassJSON {#generateallclassjson}


```4d
Function generateAllClassJSON
```

Generate JSON files for all classes using ClassInspector

---

#### generateMarkdownFromJSON {#generatemarkdownfromjson}


```4d
Function generateMarkdownFromJSON
```

Generate markdown documentation from JSON files

---

#### _generateMarkdownForClass {#_generatemarkdownforclass}


```4d
Function _generateMarkdownForClass($ClassJSON : Object) -> Text
```

Helper function to generate markdown for a single class

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ClassJSON` | `Object` | - | - |

**Returns:** `Text`

---

#### _generateFunctionMarkdown {#_generatefunctionmarkdown}


```4d
Function _generateFunctionMarkdown($Func : Object) -> Text
```

Helper function to generate markdown for a single function

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Func` | `Object` | - | - |

**Returns:** `Text`

---

#### generateAllTableJSON {#generatealltablejson}


```4d
Function generateAllTableJSON
```

Get all table names from the catalog

---

#### generateMarkdownFromTableJSON {#generatemarkdownfromtablejson}


```4d
Function generateMarkdownFromTableJSON
```

Generate markdown documentation from table JSON files

---

#### _generateMarkdownForTable {#_generatemarkdownfortable}


```4d
Function _generateMarkdownForTable($TableJSON : Object) -> Text
```

Helper function to generate markdown for a single table

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TableJSON` | `Object` | - | - |

**Returns:** `Text`

---

#### generateAllFormJSON {#generateallformjson}


```4d
Function generateAllFormJSON
```

Generate JSON files for all forms using FormInspector

---

#### discoverRelationships {#discoverrelationships}


```4d
Function discoverRelationships -> Integer
```

Discover and update relationships between Forms, Tables, and Classes

**Returns:** `Integer`

---

#### generateMarkdownFromFormJSON {#generatemarkdownfromformjson}


```4d
Function generateMarkdownFromFormJSON
```

Generate markdown documentation from form JSON files

---

#### _generateMarkdownForForm {#_generatemarkdownforform}


```4d
Function _generateMarkdownForForm($FormJSON : Object) -> Text
```

Helper function to generate markdown for a single form

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FormJSON` | `Object` | - | - |

**Returns:** `Text`

---

## 🔗 Related Items

### 📦 Related Classes

- [](.md) - Extends this class

---

*Generated from Documentation.4dm*
