---
layout : default
title : PickRequestEntity
parent : Classes
---
# PickRequestEntity

**Extends:** `Entity`

## Table of Contents

### Functions

- [OrderPickRequest() [getter]](#orderpickrequest)
- [MovementPickRequest() [getter]](#movementpickrequest)
- [modify()](#modify)
- [cancel()](#cancel)
- [despatch()](#despatch)
- [despatchOrder()](#despatchorder)
- [PartsRequested() [getter]](#partsrequested)
- [despatchConsignment()](#despatchconsignment)
- [Picked() [getter]](#picked)
- [query Picked()](#query picked)
- [PickingStarted() [getter]](#pickingstarted)
- [getNotInStockWorksOrders()](#getnotinstockworksorders)
- [Status() [getter]](#status)
- [StatusColor() [getter]](#statuscolor)
- [getWorksOrderSummaryListboxCollection()](#getworksordersummarylistboxcollection)
- [getPickedStockListboxObject()](#getpickedstocklistboxobject)
- [sendNotification()](#sendnotification)
- [sendPickedNotification()](#sendpickednotification)

---

## Functions

### OrderPickRequest {#orderpickrequest}
 `[getter]`

```4d
Function OrderPickRequest -> Boolean
```

**Returns:** `Boolean`

---

### MovementPickRequest {#movementpickrequest}
 `[getter]`

```4d
Function MovementPickRequest -> Boolean
```

**Returns:** `Boolean`

---

### modify {#modify}
 `[local]`

```4d
Function modify -> Boolean
```

**Returns:** `Boolean`

---

### cancel {#cancel}


```4d
Function cancel
```

---

### despatch {#despatch}
 `[local]`

```4d
Function despatch
```

---

### despatchOrder {#despatchorder}
 `[local]`

```4d
Function despatchOrder($Advice_NoteEntity : cs.Advice_NoteEntity)
```

---

### PartsRequested {#partsrequested}
 `[local]` `[getter]`

```4d
Function PartsRequested -> Boolean
```

**Returns:** `Boolean`

---

### despatchConsignment {#despatchconsignment}
 `[local]`

```4d
Function despatchConsignment
```

---

### Picked {#picked}
 `[local]` `[getter]`

```4d
Function Picked -> Boolean
```

**Returns:** `Boolean`

---

### query Picked {#query picked}
 `[local]`

```4d
Function query Picked($QueryEventObject : Object) -> Text
```

**Returns:** `Text`

---

### PickingStarted {#pickingstarted}
 `[local]` `[getter]`

```4d
Function PickingStarted -> Boolean
```

**Returns:** `Boolean`

---

### getNotInStockWorksOrders {#getnotinstockworksorders}
 `[local]`

```4d
Function getNotInStockWorksOrders -> cs.WorksOrderSelection
```

**Returns:** `cs.WorksOrderSelection`

---

### Status {#status}
 `[local]` `[getter]`

```4d
Function Status -> Text
```

**Returns:** `Text`

---

### StatusColor {#statuscolor}
 `[local]` `[getter]`

```4d
Function StatusColor -> Integer
```

**Returns:** `Integer`

---

### getWorksOrderSummaryListboxCollection {#getworksordersummarylistboxcollection}
 `[local]`

```4d
Function getWorksOrderSummaryListboxCollection -> Collection
```

**Returns:** `Collection`

---

### getPickedStockListboxObject {#getpickedstocklistboxobject}
 `[local]`

```4d
Function getPickedStockListboxObject -> Object
```

**Returns:** `Object`

---

### sendNotification {#sendnotification}


```4d
Function sendNotification
```

---

### sendPickedNotification {#sendpickednotification}


```4d
Function sendPickedNotification
```

---

---

*Generated from PickRequestEntity.4dm*
*Last updated: 2025-11-13T00:30:42.136Z*
