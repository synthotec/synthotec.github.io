---
layout : default
title : ClassParameter
parent : Classes
---
# ClassParameter [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ClassParameter.4dm)

📊 **Overview:** 3 Properties | 1 Constructor | 1 Functions

## 📝 Description

Metadata class representing a single parameter of a 4D class function, storing its name, type, and optional flag. Used by ClassInspector when parsing function signatures and serialising class metadata to JSON.

🕐 *Last updated: 2026-03-09T14:45:29.154Z*

---

## 📑 Table of Contents

- [📋 Properties (3)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [toObject](#toobject) → `Object`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Name` | `Text` | - | The name of the parameter |
| `Type` | `Text` | - | The data type of the parameter |
| `IsOptional` | `Boolean` | `False` | Indicates if the parameter is optional |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Name : Text; $Type : Text)
```

Creates a new parameter metadata object with the specified name and type

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Name` | `Text` | - | - |
| `$Type` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### toObject {#toobject}


```4d
Function toObject -> Object
```

Converts the parameter metadata to an object suitable for JSON serialization

**Returns:** `Object`

---

---

*Generated from ClassParameter.4dm*
