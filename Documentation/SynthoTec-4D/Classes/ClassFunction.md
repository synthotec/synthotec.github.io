---
layout : default
title : ClassFunction
parent : Classes
---
# ClassFunction [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ClassFunction.4dm)

📊 **Overview:** 8 Properties | 1 Constructor | 3 Functions

## 📝 Description

Metadata class representing a function defined in a 4D class file, storing its name, modifiers, parameters, return type, line number, and documentation comment. Used by ClassInspector to build the JSON representation of a class.

🕐 *Last updated: 2026-03-09T14:45:29.147Z*

---

## 📑 Table of Contents

- [📋 Properties (8)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [addModifier](#addmodifier) (1 param)
    - [addParameter](#addparameter) (1 param)
    - [toObject](#toobject) → `Object`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Name` | `Text` | - | The name of the function |
| `Modifiers` | `Collection` | `[]` | Collection of function modifiers (local, exposed, etc.) |
| `IsGetter` | `Boolean` | `False` | Indicates if this is a getter function |
| `IsSetter` | `Boolean` | `False` | Indicates if this is a setter function |
| `Parameters` | `Collection` | `[]` | Collection of ClassParameter objects defining function parameters |
| `ReturnType` | `Text` | `""` | The return type of the function |
| `LineNumber` | `Integer` | `0` | Line number where the function is defined in the source file |
| `DocComment` | `Text` | `""` | Documentation comment for the function |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Name : Text)
```

Creates a new class function metadata object with the specified function name

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Name` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### addModifier {#addmodifier}


```4d
Function addModifier($Modifier : Text)
```

Adds a modifier (e.g., "local", "exposed") to the function's modifiers collection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Modifier` | `Text` | - | - |

---

#### addParameter {#addparameter}


```4d
Function addParameter($Parameter : cs.ClassParameter)
```

Adds a parameter definition to the function's parameters collection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameter` | `cs.ClassParameter` | - | - |

---

#### toObject {#toobject}


```4d
Function toObject -> Object
```

Converts the function metadata to an object suitable for JSON serialization

**Returns:** `Object`

---

---

*Generated from ClassFunction.4dm*
