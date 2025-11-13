---
layout : default
title : QueryEventHandler
parent : Classes
---
# QueryEventHandler

📊 **Overview:** 6 Properties | 1 Constructor | 1 Functions | 2 Getters

🕐 *Last updated: 2025-11-13T16:46:52.567Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#-properties)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (1):**

- [setResult](#setresult) (2 params)

**🔍 Getters (2):**

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

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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

### 🔍 Getters

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
