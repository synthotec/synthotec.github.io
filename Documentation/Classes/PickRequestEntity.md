---
layout : default
title : PickRequestEntity
parent : Classes
---
# PickRequestEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PickRequestEntity.4dm)

📊 **Overview:** 11 Functions | 7 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:18:20.915Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [modify](#modify) → `$Modified : Boolean` 🖥️
  - [cancel](#cancel)
  - [despatch](#despatch) 🖥️
  - [despatchOrder](#despatchorder) (1 param) 🖥️
  - [despatchConsignment](#despatchconsignment) 🖥️
  - [query Picked](#query picked) (1 param) → `Text` 🖥️
  - [getNotInStockWorksOrders](#getnotinstockworksorders) → `$WorksOrderSelection : cs.WorksOrderSelection` 🖥️
  - [getWorksOrderSummaryListboxCollection](#getworksordersummarylistboxcollection) → `$Collection : Collection` 🖥️
  - [getPickedStockListboxObject](#getpickedstocklistboxobject) → `$Object : Object` 🖥️
  - [sendNotification](#sendnotification)
  - [sendPickedNotification](#sendpickednotification)
  - [OrderPickRequest](#orderpickrequest) → `Boolean`
  - [MovementPickRequest](#movementpickrequest) → `Boolean`
  - [PartsRequested](#partsrequested) → `Boolean`
  - [Picked](#picked) → `Boolean`
  - [PickingStarted](#pickingstarted) → `Boolean`
  - [Status](#status) → `Text`
  - [StatusColor](#statuscolor) → `Integer`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### modify {#modify}
 `[🖥️ local]`

```4d
Function modify -> $Modified : Boolean
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
Function getNotInStockWorksOrders -> $WorksOrderSelection : cs.WorksOrderSelection
```

**Returns:** `cs.WorksOrderSelection`

---

#### getWorksOrderSummaryListboxCollection {#getworksordersummarylistboxcollection}
 `[🖥️ local]`

```4d
Function getWorksOrderSummaryListboxCollection -> $Collection : Collection
```

**Returns:** `Collection`

---

#### getPickedStockListboxObject {#getpickedstocklistboxobject}
 `[🖥️ local]`

```4d
Function getPickedStockListboxObject -> $Object : Object
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

### Getters

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

## Related Items {#related-items}

### 🗂️ Tables

- [PickRequest](../Tables/PickRequest.md) - Source table for this ORDA class

### � Related Classes

- [PickRequest](PickRequest.md) - ORDA DataClass class for PickRequest table

---

*Generated from PickRequestEntity.4dm*
