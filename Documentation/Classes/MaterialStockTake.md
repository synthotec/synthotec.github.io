---
layout : default
title : MaterialStockTake
parent : Classes
---
# MaterialStockTake [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MaterialStockTake.4dm)

📊 **Overview:** 5 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T16:35:58.760Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
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

**Returns:** `Date`

---

#### getLastStockTakeAmount {#getlaststocktakeamount}
 `[🖥️ local]`

```4d
Function getLastStockTakeAmount($MaterialID : Integer) -> Real
```

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

**Returns:** `cs.MaterialStockTakeSelection`

---

#### restViewResults {#restviewresults}


```4d
Function restViewResults($RestPostDataObject : Object) -> Object
```

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

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [MaterialStockTake](../Tables/MaterialStockTake.md) - Source table for this ORDA class

---

*Generated from MaterialStockTake.4dm*
