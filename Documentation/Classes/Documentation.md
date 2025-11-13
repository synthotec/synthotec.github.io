---
layout : default
title : Documentation
parent : Classes
---
# Documentation

📊 **Overview:** 1 Properties | 1 Constructor | 10 Functions

## 📝 Description

🗨️ This.CompiledClassesObject:=This.getCompiledClassesObject($CompileCode)

🕐 *Last updated: 2025-11-13T02:47:32.518Z*

---

## 📑 Table of Contents

### 📋 Properties (1)

- [CompiledClassesObject](#compiledclassesobject) : `Object`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Functions (10):**

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

---

*Generated from Documentation.4dm*
