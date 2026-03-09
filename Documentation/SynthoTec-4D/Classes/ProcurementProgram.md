---
layout : default
title : ProcurementProgram
parent : Classes
---
# ProcurementProgram [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProcurementProgram.4dm)

📊 **Overview:** 14 Properties | 1 Constructor | 5 Functions

## 📝 Description

Parses a customer-supplied procurement schedule pasted from the clipboard as tab-delimited data, identifying column positions for item numbers, order status, quantities, due dates, warehouse codes, and VMI flags. Produces a collection of ProcurementProgramLine objects for review and processing.

🕐 *Last updated: 2026-03-09T14:45:30.656Z*

---

## 📑 Table of Contents

- [📋 Properties (14)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [calculateGoodsInTransit](#calculategoodsintransit)
    - [closeOrdersNotInProgram](#closeordersnotinprogram)
    - [reconcileGit](#reconcilegit)
    - [process](#process)
    - [deleteForecastOrders](#deleteforecastorders) → `$NotDropped : cs.Customer_OrderSelection`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Lines` | `Collection` | - | Collection of cs.ProcurementProgramLine objects parsed from clipboard data |
| `ItemNumberIndex` | `Integer` | `-1` | Column index for item number in tab-delimited input |
| `StatusIndex` | `Integer` | `-1` | Column index for order status (FORECAST/BACKLOG/order number) in input |
| `QuantityIndex` | `Integer` | `-1` | Column index for quantity in input |
| `DueDateIndex` | `Integer` | `-1` | Column index for due date in input |
| `ItemDescriptionIndex` | `Integer` | `-1` | Column index for item description in input |
| `VmiIndex` | `Integer` | `-1` | Column index for VMI (Vendor Managed Inventory) flag in input |
| `WarehouseIndex` | `Integer` | `-1` | Column index for warehouse location code in input |
| `LastDeliveryQtyIndex` | `Integer` | `-1` | Column index for last delivery quantity |
| `OrderPostNbIndex` | `Integer` | `-1` | Column index for order/post number of last delivery |
| `PackingListNbIndex` | `Integer` | `-1` | Column index for packing list (advice note) number |
| `ErrorOccurred` | `Boolean` | - | True if parsing failed due to missing columns or invalid format |
| `GoodsInTransitDictionary` | `Object` | `{}` | Maps Product_Option ID strings to goods-in-transit quantities for reconciliation |
| `ds` | `cs.DataStore` | `DataStore(0)` | Reference to main datastore |

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

#### calculateGoodsInTransit {#calculategoodsintransit}


```4d
Function calculateGoodsInTransit
```

Calculates goods-in-transit quantities by comparing last packing list deliveries against CofC receipt records; populates GoodsInTransitDictionary

---

#### closeOrdersNotInProgram {#closeordersnotinprogram}


```4d
Function closeOrdersNotInProgram
```

Close orders not seen in current program by setting Ordered=Delivered

---

#### reconcileGit {#reconcilegit}


```4d
Function reconcileGit
```

Reduce order quantities chronologically based on goods in transit

---

#### process {#process}


```4d
Function process
```

Processes all procurement program lines with GIT reconciliation

---

#### deleteForecastOrders {#deleteforecastorders}


```4d
Function deleteForecastOrders -> $NotDropped : cs.Customer_OrderSelection
```

Deletes all existing forecast orders created by procurement program processing and returns any records that could not be dropped

**Returns:** `cs.Customer_OrderSelection`

---

---

*Generated from ProcurementProgram.4dm*
