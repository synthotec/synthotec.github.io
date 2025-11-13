---
layout : default
title : QueryEventHandler
parent : Classes
---
# QueryEventHandler

📊 **Overview:** 6 Properties | 1 Constructor | 1 Functions | 2 Getters

🕐 *Last updated: 2025-11-13T01:17:24.397Z*

---

## 📑 Table of Contents

### 📋 Properties (6)

- [value](#value) : `Variant`
- [operator](#operator) : `Text`
- [eventKind](#eventkind) : `Text`
- [attributeName](#attributename) : `Text`
- [dataClassName](#dataclassname) : `Text`
- [QueryEventObject](#queryeventobject) : `Object`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Functions (1):**

- [setResult](#setresult) (2 params)

**🔍 Getters (2):**

- [valueType](#valuetype) → `Integer`
- [booleanResult](#booleanresult) → `Variant`

---

## 📋 Properties

### Quick Reference

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `value` | `Variant` | - |  |
| `operator` | `Text` | - |  |
| `eventKind` | `Text` | - |  |
| `attributeName` | `Text` | - |  |
| `dataClassName` | `Text` | - |  |
| `QueryEventObject` | `Object` | - |  |

### Detailed Information

#### value {#value}

**Type:** `Variant`

---

#### operator {#operator}

**Type:** `Text`

---

#### eventKind {#eventkind}

**Type:** `Text`

---

#### attributeName {#attributename}

**Type:** `Text`

---

#### dataClassName {#dataclassname}

**Type:** `Text`

---

#### QueryEventObject {#queryeventobject}

**Type:** `Object`

---

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
