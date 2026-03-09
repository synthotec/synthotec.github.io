---
layout : default
title : ClassProperty
parent : Classes
---
# ClassProperty [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ClassProperty.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 2 Functions

## 📝 Description

Metadata class representing a property declaration in a 4D class, storing its name, type, default value, line number, and inline documentation comment. Used by ClassInspector to capture class structure for JSON output.

🕐 *Last updated: 2026-03-09T14:45:29.164Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setDefault](#setdefault) (1 param)
    - [toObject](#toobject) → `Object`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Name` | `Text` | - | Property name |
| `Type` | `Text` | - | Property data type (Text, Integer, Object, etc.) |
| `HasDefault` | `Boolean` | `False` | Whether property has a default value assigned |
| `DefaultValue` | `Text` | `""` | Default value string if HasDefault is true |
| `LineNumber` | `Integer` | `0` | Line number where property is declared |
| `DocComment` | `Text` | `""` | Inline comment documenting the property |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Name : Text; $Type : Text)
```

Creates metadata for a class property with name and type

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Name` | `Text` | - | - |
| `$Type` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### setDefault {#setdefault}


```4d
Function setDefault($Value : Text)
```

Sets the default value for this property

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Value` | `Text` | - | - |

---

#### toObject {#toobject}


```4d
Function toObject -> Object
```

Converts property metadata to JSON-serializable object

**Returns:** `Object`

---

---

*Generated from ClassProperty.4dm*
