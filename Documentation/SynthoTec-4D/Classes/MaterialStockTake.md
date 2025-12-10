---
layout : default
title : MaterialStockTake
parent : Classes
---
# MaterialStockTake [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MaterialStockTake.4dm)

📊 **Overview:** 5 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-12-10T11:45:23.317Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getLastStockTakeDate](#getlaststocktakedate) → `Date` 🖥️
    - [getLastStockTakeAmount](#getlaststocktakeamount) (1 param) → `Real` 🖥️
    - [getLastStockTakeSelection](#getlaststocktakeselection) → `cs.MaterialStockTakeSelection` 🖥️
    - [restViewResults](#restviewresults) (1 param) → `Object`
    - [restRemoveEntry](#restremoveentry) (1 param) → `Object`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getLastStockTakeDate {#getlaststocktakedate}
 `[🖥️ local]`

```4d
Function getLastStockTakeDate -> Date
```

Returns the date of the most recent primary stock take

**Returns:** `Date`

---

#### getLastStockTakeAmount {#getlaststocktakeamount}
 `[🖥️ local]`

```4d
Function getLastStockTakeAmount($MaterialID : Integer) -> Real
```

Returns total amount in Kg for a specific material from the last primary stock take

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MaterialID` | `Integer` | - | - |

**Returns:** `Real`

---

#### getLastStockTakeSelection {#getlaststocktakeselection}
 `[🖥️ local]`

```4d
Function getLastStockTakeSelection -> cs.MaterialStockTakeSelection
```

Returns entity selection of all primary stock take entries from the most recent stock take date

**Returns:** `cs.MaterialStockTakeSelection`

---

#### restViewResults {#restviewresults}


```4d
Function restViewResults($RestPostDataObject : Object) -> Object
```

REST endpoint to display stock take results for current date in mobile warehouse app

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restRemoveEntry {#restremoveentry}


```4d
Function restRemoveEntry($RestPostDataObject : Object) -> Object
```

REST endpoint to remove a stock take entry after confirmation in mobile app

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [MaterialStockTake](../Tables/MaterialStockTake.md) - ORDA DataClass class for MaterialStockTake table

### � Forms

- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from MaterialStockTake.4dm*
