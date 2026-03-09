---
layout : default
title : MaterialStockEntity
parent : Classes
---
# MaterialStockEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MaterialStockEntity.4dm)

📊 **Overview:** 3 Functions

## 📝 Description

Entity representing a raw material stock record (a specific batch/pallet at a warehouse location), with helpers for warehouse listbox display, movement logging (with RMC, location, staff, and comment), and automatic location clearance when quantity drops to zero.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.066Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getStockListBoxObject](#getstocklistboxobject) → `Object` 🖥️
    - [log](#log) (4 params) → `$MaterialStockLogEntity : cs.MaterialStockLogEntity` 🖥️
    - [clearLocationIfZeroQuantity](#clearlocationifzeroquantity)
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getStockListBoxObject {#getstocklistboxobject}
 `[🖥️ local]`

```4d
Function getStockListBoxObject -> Object
```

Returns object with stock data formatted for warehouse listbox display

**Returns:** `Object`

---

#### log {#log}
 `[🖥️ local]`

```4d
Function log($Quantity : Integer; $StaffEntity : cs.StaffEntity; $MaterialCheckHistoryEntity : cs.MaterialCheckHistoryEntity; $Comment : Text) -> $MaterialStockLogEntity : cs.MaterialStockLogEntity
```

Creates and saves a MaterialStockLog entry recording the quantity change, location, staff member, optional check history link, and comment

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Quantity` | `Integer` | - | - |
| `$StaffEntity` | `cs.StaffEntity` | - | - |
| `$MaterialCheckHistoryEntity` | `cs.MaterialCheckHistoryEntity` | - | - |
| `$Comment` | `Text` | - | - |

**Returns:** `cs.MaterialStockLogEntity`

---

#### clearLocationIfZeroQuantity {#clearlocationifzeroquantity}


```4d
Function clearLocationIfZeroQuantity
```

Clears the location assignment on this stock item if its quantity has dropped to zero or below

---

## Related Items {#related-items}

### 🗂️ Tables

- [MaterialStock](../Tables/MaterialStock.md) - ORDA Entity class for MaterialStock table

### � Related Classes

- [MaterialStock](MaterialStock.md) - ORDA DataClass class for MaterialStock table

### � Forms

- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from MaterialStockEntity.4dm*
