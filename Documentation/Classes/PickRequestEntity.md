---
layout : default
title : PickRequestEntity
parent : Classes
---
# PickRequestEntity

📊 **Overview:** 11 Functions | 7 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T12:58:34.287Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (11):**

- [modify](#modify) → `Boolean` 🖥️
- [cancel](#cancel)
- [despatch](#despatch) 🖥️
- [despatchOrder](#despatchorder) (1 param) 🖥️
- [despatchConsignment](#despatchconsignment) 🖥️
- [query Picked](#query picked) (1 param) → `Text` 🖥️
- [getNotInStockWorksOrders](#getnotinstockworksorders) → `cs.WorksOrderSelection` 🖥️
- [getWorksOrderSummaryListboxCollection](#getworksordersummarylistboxcollection) → `Collection` 🖥️
- [getPickedStockListboxObject](#getpickedstocklistboxobject) → `Object` 🖥️
- [sendNotification](#sendnotification)
- [sendPickedNotification](#sendpickednotification)

**🔍 Getters (7):**

- [OrderPickRequest](#orderpickrequest) → `Boolean`
- [MovementPickRequest](#movementpickrequest) → `Boolean`
- [PartsRequested](#partsrequested) → `Boolean`
- [Picked](#picked) → `Boolean`
- [PickingStarted](#pickingstarted) → `Boolean`
- [Status](#status) → `Text`
- [StatusColor](#statuscolor) → `Integer`

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### modify {#modify}
 `[🖥️ local]`

```4d
Function modify -> Boolean
```

**Returns:** `Boolean`

---

#### cancel {#cancel}


```4d
Function cancel
```

---

#### despatch {#despatch}
 `[🖥️ local]`

```4d
Function despatch
```

---

#### despatchOrder {#despatchorder}
 `[🖥️ local]`

```4d
Function despatchOrder($Advice_NoteEntity : cs.Advice_NoteEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Advice_NoteEntity` | `cs.Advice_NoteEntity` | - | - |

---

#### despatchConsignment {#despatchconsignment}
 `[🖥️ local]`

```4d
Function despatchConsignment
```

---

#### query Picked {#query picked}
 `[🖥️ local]`

```4d
Function query Picked($QueryEventObject : Object) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

**Returns:** `Text`

---

#### getNotInStockWorksOrders {#getnotinstockworksorders}
 `[🖥️ local]`

```4d
Function getNotInStockWorksOrders -> cs.WorksOrderSelection
```

**Returns:** `cs.WorksOrderSelection`

---

#### getWorksOrderSummaryListboxCollection {#getworksordersummarylistboxcollection}
 `[🖥️ local]`

```4d
Function getWorksOrderSummaryListboxCollection -> Collection
```

**Returns:** `Collection`

---

#### getPickedStockListboxObject {#getpickedstocklistboxobject}
 `[🖥️ local]`

```4d
Function getPickedStockListboxObject -> Object
```

**Returns:** `Object`

---

#### sendNotification {#sendnotification}


```4d
Function sendNotification
```

---

#### sendPickedNotification {#sendpickednotification}


```4d
Function sendPickedNotification
```

---

### 🔍 Getters

#### OrderPickRequest {#orderpickrequest}
 `[🔍 getter]`

```4d
Function OrderPickRequest -> Boolean
```

**Returns:** `Boolean`

---

#### MovementPickRequest {#movementpickrequest}
 `[🔍 getter]`

```4d
Function MovementPickRequest -> Boolean
```

**Returns:** `Boolean`

---

#### PartsRequested {#partsrequested}
 `[🖥️ local, 🔍 getter]`

```4d
Function PartsRequested -> Boolean
```

**Returns:** `Boolean`

---

#### Picked {#picked}
 `[🖥️ local, 🔍 getter]`

```4d
Function Picked -> Boolean
```

**Returns:** `Boolean`

---

#### PickingStarted {#pickingstarted}
 `[🖥️ local, 🔍 getter]`

```4d
Function PickingStarted -> Boolean
```

**Returns:** `Boolean`

---

#### Status {#status}
 `[🖥️ local, 🔍 getter]`

```4d
Function Status -> Text
```

**Returns:** `Text`

---

#### StatusColor {#statuscolor}
 `[🖥️ local, 🔍 getter]`

```4d
Function StatusColor -> Integer
```

**Returns:** `Integer`

---

## 🔗 Related Items

### 🗂️ Used By Tables

- [PickRequest](../Tables/PickRequest.md) - Entity class

---

*Generated from PickRequestEntity.4dm*
