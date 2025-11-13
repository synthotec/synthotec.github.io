---
layout : default
title : QueryEventHandler
parent : Classes
---
# QueryEventHandler [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/QueryEventHandler.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 1 Functions | 2 Getters

🕐 *Last updated: 2025-11-13T23:49:47.311Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#-properties)
- [🏗️ Constructor](#-constructor) (1 param)
- [⚙️ Functions](#️-functions)
  - [setResult](#setresult) (2 params)
  - [valueType](#valuetype) → `Integer`
  - [booleanResult](#booleanresult) → `Variant`
---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `value` | `Variant` | - | - |
| `operator` | `Text` | - | - |
| `eventKind` | `Text` | - | - |
| `attributeName` | `Text` | - | - |
| `dataClassName` | `Text` | - | - |
| `QueryEventObject` | `Object` | - | - |

## 🏗️ Constructor

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

## ⚙️ Functions

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

#### valueType {#valuetype}
 `[🔍 getter]`

```4d
Function valueType -> Integer
```

**Returns:** `Integer`

---

#### booleanResult {#booleanresult}
 `[🔍 getter]`

```4d
Function booleanResult -> Variant
```

**Returns:** `Variant`

---

---

*Generated from QueryEventHandler.4dm*
