# PickRequest

**Extends:** `DataClass`

## Table of Contents

### Functions

- [create()](#create)
- [newUsingEntry()](#newusingentry)
- [getOpenRequests()](#getopenrequests)
- [restInitialPage()](#restinitialpage)
- [restPickPage()](#restpickpage)
- [restUnpickStock()](#restunpickstock)
- [restViewStock()](#restviewstock)
- [restScanStock()](#restscanstock)
- [restSelectOrderToPickAgainst()](#restselectordertopickagainst)
- [restPickAgainstOrder()](#restpickagainstorder)
- [checkForPickedPickRequests()](#checkforpickedpickrequests)

---

## Functions

### create {#create}
 `[local]`

```4d
Function create -> cs.PickRequestEntity
```

**Returns:** `cs.PickRequestEntity`

---

### newUsingEntry {#newusingentry}
 `[local]`

```4d
Function newUsingEntry -> cs.PickRequestEntity
```

**Returns:** `cs.PickRequestEntity`

---

### getOpenRequests {#getopenrequests}
 `[local]`

```4d
Function getOpenRequests -> cs.PickRequestSelection
```

**Returns:** `cs.PickRequestSelection`

---

### restInitialPage {#restinitialpage}
 `[exposed]`

```4d
Function restInitialPage($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restPickPage {#restpickpage}
 `[exposed]`

```4d
Function restPickPage($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restUnpickStock {#restunpickstock}
 `[exposed]`

```4d
Function restUnpickStock($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restViewStock {#restviewstock}
 `[exposed]`

```4d
Function restViewStock($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restScanStock {#restscanstock}
 `[exposed]`

```4d
Function restScanStock($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restSelectOrderToPickAgainst {#restselectordertopickagainst}
 `[exposed]`

```4d
Function restSelectOrderToPickAgainst($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restPickAgainstOrder {#restpickagainstorder}
 `[exposed]`

```4d
Function restPickAgainstOrder($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### checkForPickedPickRequests {#checkforpickedpickrequests}


```4d
Function checkForPickedPickRequests
```

---

---

*Generated from PickRequest.4dm*
*Last updated: 2025-11-12T17:17:32.035Z*
