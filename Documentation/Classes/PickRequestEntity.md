---
layout : default
title : PickRequestEntity
parent : Classes
---
# PickRequestEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PickRequestEntity.4dm)

📊 **Overview:** 10 Functions | 7 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:45:50.674Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [modify](#modify) → `$Modified : Boolean` 🖥️
    - [cancel](#cancel)
    - [despatch](#despatch) 🖥️
    - [despatchOrder](#despatchorder) (1 param) 🖥️
    - [despatchConsignment](#despatchconsignment) 🖥️
    - [getNotInStockWorksOrders](#getnotinstockworksorders) → `$WorksOrderSelection : cs.WorksOrderSelection` 🖥️
    - [getWorksOrderSummaryListboxCollection](#getworksordersummarylistboxcollection) → `$Collection : Collection` 🖥️
    - [getPickedStockListboxObject](#getpickedstocklistboxobject) → `$Object : Object` 🖥️
    - [sendNotification](#sendnotification)
    - [sendPickedNotification](#sendpickednotification)
  - **Properties (Getters/Setters/Query/OrderBy)**
    - [MovementPickRequest](#movementpickrequest) 🔍 → `Boolean`
    - [OrderPickRequest](#orderpickrequest) 🔍 → `Boolean`
    - [PartsRequested](#partsrequested) 🔍 → `Boolean`
    - [Picked](#picked) 🔍 🔎 → `Boolean`
    - [PickingStarted](#pickingstarted) 🔍 → `Boolean`
    - [Status](#status) 🔍 → `Text`
    - [StatusColor](#statuscolor) 🔍 → `Integer`
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

### Properties (Getters/Setters/Query/OrderBy)

#### MovementPickRequest {#movementpickrequest}
 `[🔍 get only]`

```4d
Function get MovementPickRequest -> Boolean
```

**Returns:** `Boolean`

---

#### OrderPickRequest {#orderpickrequest}
 `[🔍 get only]`

```4d
Function get OrderPickRequest -> Boolean
```

**Returns:** `Boolean`

---

#### PartsRequested {#partsrequested}
 `[🔍 get only, 🖥️ local]`

```4d
Function get PartsRequested -> Boolean
```

**Returns:** `Boolean`

---

#### Picked {#picked}
 `[🔍 get, 🔎 query, 🖥️ local]`

```4d
Function get Picked -> Boolean
Function query Picked($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

**Returns:** `Boolean`

---

#### PickingStarted {#pickingstarted}
 `[🔍 get only, 🖥️ local]`

```4d
Function get PickingStarted -> Boolean
```

**Returns:** `Boolean`

---

#### Status {#status}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Status -> Text
```

**Returns:** `Text`

---

#### StatusColor {#statuscolor}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StatusColor -> Integer
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
