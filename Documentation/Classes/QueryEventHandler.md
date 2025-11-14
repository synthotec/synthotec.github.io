---
layout : default
title : QueryEventHandler
parent : Classes
---
# QueryEventHandler [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/QueryEventHandler.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 1 Functions | 2 Getters

🕐 *Last updated: 2025-11-14T16:45:50.847Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setResult](#setresult) (2 params)
  - **Properties (Getters/Setters/Query/OrderBy)**
    - [booleanResult](#booleanresult) 🔍 → `Variant`
    - [valueType](#valuetype) 🔍 → `Integer`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `value` | `Variant` | - | - |
| `operator` | `Text` | - | - |
| `eventKind` | `Text` | - | - |
| `attributeName` | `Text` | - | - |
| `dataClassName` | `Text` | - | - |
| `QueryEventObject` | `Object` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($QueryEventObject : Object)
```

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

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryText` | `Text` | - | - |
| `$QueryParameters` | `Collection` | - | - |

---

### Properties (Getters/Setters/Query/OrderBy)

#### booleanResult {#booleanresult}
 `[🔍 get only]`

```4d
Function get booleanResult -> Variant
```

**Returns:** `Variant`

---

#### valueType {#valuetype}
 `[🔍 get only]`

```4d
Function get valueType -> Integer
```

**Returns:** `Integer`

---

---

*Generated from QueryEventHandler.4dm*
