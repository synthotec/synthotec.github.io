# MaterialStockTake

**Extends:** `DataClass`

## Table of Contents

### Functions

- [getLastStockTakeDate()](#getlaststocktakedate)
- [getLastStockTakeAmount()](#getlaststocktakeamount)
- [getLastStockTakeSelection()](#getlaststocktakeselection)
- [restViewResults()](#restviewresults)
- [restRemoveEntry()](#restremoveentry)

---

## Functions

### getLastStockTakeDate {#getlaststocktakedate}
 `[local]`

```4d
Function getLastStockTakeDate -> Date
```

**Returns:** `Date`

---

### getLastStockTakeAmount {#getlaststocktakeamount}
 `[local]`

```4d
Function getLastStockTakeAmount($MaterialID : Integer) -> Real
```

**Returns:** `Real`

---

### getLastStockTakeSelection {#getlaststocktakeselection}
 `[local]`

```4d
Function getLastStockTakeSelection -> cs.MaterialStockTakeSelection
```

**Returns:** `cs.MaterialStockTakeSelection`

---

### restViewResults {#restviewresults}
 `[exposed]`

```4d
Function restViewResults($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restRemoveEntry {#restremoveentry}
 `[exposed]`

```4d
Function restRemoveEntry($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

---

*Generated from MaterialStockTake.4dm*
*Last updated: 2025-11-12T17:17:31.844Z*
