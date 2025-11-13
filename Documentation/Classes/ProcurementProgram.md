---
layout : default
title : ProcurementProgram
parent : Classes
---
# ProcurementProgram

📊 **Overview:** 10 Properties | 1 Constructor | 1 Functions | 2 Getters

🕐 *Last updated: 2025-11-13T13:52:49.809Z*

---

## 📑 Table of Contents

### 📋 Properties (10)

- [Lines](#lines) : `Collection`
- [ItemNumberIndex](#itemnumberindex)
- [StatusIndex](#statusindex)
- [QuantityIndex](#quantityindex)
- [DueDateIndex](#duedateindex)
- [ItemDescriptionIndex](#itemdescriptionindex)
- [VmiIndex](#vmiindex)
- [WarehouseIndex](#warehouseindex)
- [ErrorOccurred](#erroroccurred) : `Boolean`
- [ds](#ds)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (1):**

- [process](#process)

**🔍 Getters (2):**

- [AllLinesActioned](#alllinesactioned) → `Boolean`
- [UnactionedLines](#unactionedlines) → `Collection`

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Lines` | `Collection` | - | - |
| `ItemNumberIndex` | *Not specified* | `-1` | - |
| `StatusIndex` | *Not specified* | `-1` | - |
| `QuantityIndex` | *Not specified* | `-1` | - |
| `DueDateIndex` | *Not specified* | `-1` | - |
| `ItemDescriptionIndex` | *Not specified* | `-1` | - |
| `VmiIndex` | *Not specified* | `-1` | - |
| `WarehouseIndex` | *Not specified* | `-1` | - |
| `ErrorOccurred` | `Boolean` | - | - |
| `ds` | *Not specified* | `DataStore(0)` | - |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($ClipboardText : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ClipboardText` | `Text` | - | - |

---

### ⚙️ Regular Functions

#### process {#process}


```4d
Function process
```

---

### 🔍 Getters

#### AllLinesActioned {#alllinesactioned}
 `[🔍 getter]`

```4d
Function AllLinesActioned -> Boolean
```

**Returns:** `Boolean`

---

#### UnactionedLines {#unactionedlines}
 `[🔍 getter]`

```4d
Function UnactionedLines -> Collection
```

**Returns:** `Collection`

---

---

*Generated from ProcurementProgram.4dm*
