---
layout : default
title : QueryEventHandler
parent : Classes
---
# QueryEventHandler [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/QueryEventHandler.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 1 Functions | 2 Getters

## 📝 Description

Wraps a 4D ORDA query event object, providing named access to the queried value, operator, event kind, attribute name, and dataclass name. Used by virtual attribute query handlers to construct and return custom query results.

🕐 *Last updated: 2026-03-09T14:45:30.945Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setResult](#setresult) (2 params)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [booleanResult](#booleanresult) 🔍 → `Variant`
    - [valueType](#valuetype) 🔍 → `Integer`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `value` | `Variant` | - | Value being compared in the query |
| `operator` | `Text` | - | Comparison operator (==, !=, <, >, etc.) |
| `eventKind` | `Text` | - | Type of query event |
| `attributeName` | `Text` | - | Name of the attribute being queried |
| `dataClassName` | `Text` | - | Name of the dataclass being queried |
| `QueryEventObject` | `Object` | - | Original query event object from 4D |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($QueryEventObject : Object)
```

Creates query event handler from 4D query event object for custom query processing

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### setResult {#setresult}


```4d
Function setResult($QueryText : Text; $QueryParameters : Collection)
```

Sets the query result with custom query text and parameters

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryText` | `Text` | - | - |
| `$QueryParameters` | `Collection` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### booleanResult {#booleanresult}
 `[🔍 get only]`

```4d
Function get booleanResult -> Variant
```

Returns the boolean result for equality/inequality operators, Null if not boolean comparison

**Returns:** `Variant`

---

#### valueType {#valuetype}
 `[🔍 get only]`

```4d
Function get valueType -> Integer
```

Returns the 4D value type of the query comparison value

**Returns:** `Integer`

---

---

*Generated from QueryEventHandler.4dm*
