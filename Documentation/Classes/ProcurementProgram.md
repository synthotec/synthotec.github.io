---
layout : default
title : ProcurementProgram
parent : Classes
---
# ProcurementProgram [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProcurementProgram.4dm)

📊 **Overview:** 10 Properties | 1 Constructor | 1 Functions | 2 Getters

🕐 *Last updated: 2025-11-14T00:07:28.571Z*

---

## 📑 Table of Contents

- [📋 Properties (10)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - [process](#process)
  - [AllLinesActioned](#alllinesactioned) → `Boolean`
  - [UnactionedLines](#unactionedlines) → `Collection`
---

## Properties {#properties}

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

## Constructor {#constructor}

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

## Functions {#functions}

### Regular Functions

#### process {#process}


```4d
Function process
```

---

### Getters

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
