---
layout : default
title : ProcurementProgram
parent : Classes
---
# ProcurementProgram [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProcurementProgram.4dm)

📊 **Overview:** 10 Properties | 1 Constructor | 1 Functions | 2 Getters

🕐 *Last updated: 2025-12-10T11:45:23.820Z*

---

## 📑 Table of Contents

- [📋 Properties (10)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [process](#process)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [AllLinesActioned](#alllinesactioned) 🔍 → `Boolean`
    - [UnactionedLines](#unactionedlines) 🔍 → `Collection`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Lines` | `Collection` | - | Collection of cs.ProcurementProgramLine objects parsed from clipboard data |
| `ItemNumberIndex` | *Not specified* | `-1` | Column index for item number in tab-delimited input |
| `StatusIndex` | *Not specified* | `-1` | Column index for order status (FORECAST/BACKLOG/order number) in input |
| `QuantityIndex` | *Not specified* | `-1` | Column index for quantity in input |
| `DueDateIndex` | *Not specified* | `-1` | Column index for due date in input |
| `ItemDescriptionIndex` | *Not specified* | `-1` | Column index for item description in input |
| `VmiIndex` | *Not specified* | `-1` | Column index for VMI (Vendor Managed Inventory) flag in input |
| `WarehouseIndex` | *Not specified* | `-1` | Column index for warehouse location code in input |
| `ErrorOccurred` | `Boolean` | - | True if parsing failed due to missing columns or invalid format |
| `ds` | *Not specified* | `DataStore(0)` | Reference to main datastore |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($ClipboardText : Text)
```

Parses tab-delimited procurement program data from clipboard and creates ProcurementProgramLine objects for each row

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

Processes all procurement program lines by executing assigned actions (create orders, create forecasts, update orders, etc.)

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### AllLinesActioned {#alllinesactioned}
 `[🔍 get only]`

```4d
Function get AllLinesActioned -> Boolean
```

Returns true if all lines in the procurement program have an action assigned

**Returns:** `Boolean`

---

#### UnactionedLines {#unactionedlines}
 `[🔍 get only]`

```4d
Function get UnactionedLines -> Collection
```

Returns collection of ProcurementProgramLine objects that have no action assigned

**Returns:** `Collection`

---

---

*Generated from ProcurementProgram.4dm*
