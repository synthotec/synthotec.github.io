---
layout : default
title : PickRequestEntity
parent : Classes
---
# PickRequestEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PickRequestEntity.4dm)

📊 **Overview:** 10 Functions | 7 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:12.584Z*

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
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
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

Opens UI dialog to create or modify pick request details; allows customer/date selection; returns true if saved successfully

**Returns:** `Boolean`

---

#### cancel {#cancel}


```4d
Function cancel
```

Cancels pick request and releases all associated stock back to BoxLabels and Pallets; unlocks and drops all related entities

---

#### despatch {#despatch}
 `[🖥️ local]`

```4d
Function despatch
```

Validates picking is complete and checks unpicked items, creates Advice Note with transport details, and saves despatch transaction; displays alerts for validation errors

---

#### despatchOrder {#despatchorder}
 `[🖥️ local]`

```4d
Function despatchOrder($Advice_NoteEntity : cs.Advice_NoteEntity)
```

Moves picked boxes and pallets to Advice Note, updates customer orders with pallet/box assignments, marks orders as picked, and unlocks all entities after transaction commit

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

Not yet implemented; would handle movement/consignment despatch workflow

---

#### getNotInStockWorksOrders {#getnotinstockworksorders}
 `[🖥️ local]`

```4d
Function getNotInStockWorksOrders -> $WorksOrderSelection : cs.WorksOrderSelection
```

Returns works orders in pick request that don't have enough available stock; used for validation before despatch

**Returns:** `cs.WorksOrderSelection`

---

#### getWorksOrderSummaryListboxCollection {#getworksordersummarylistboxcollection}
 `[🖥️ local]`

```4d
Function getWorksOrderSummaryListboxCollection -> $Collection : Collection
```

Returns collection of works order objects with picked quantities and color-coded stock availability for UI listbox display

**Returns:** `Collection`

---

#### getPickedStockListboxObject {#getpickedstocklistboxobject}
 `[🖥️ local]`

```4d
Function getPickedStockListboxObject -> $Object : Object
```

Returns object with collection of picked boxes/pallets, metadata (box count, pallet count) for UI listbox display

**Returns:** `Object`

---

#### sendNotification {#sendnotification}


```4d
Function sendNotification
```

Sends HTML email notification with pick request details, order summary, and transport instruction attachment to distribution group

---

#### sendPickedNotification {#sendpickednotification}


```4d
Function sendPickedNotification
```

Sends HTML email with detailed table of picked boxes including pallet IDs, box numbers, works orders, and quantities for each order

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### MovementPickRequest {#movementpickrequest}
 `[🔍 get only]`

```4d
Function get MovementPickRequest -> Boolean
```

Returns true if this pick request is for inventory movement (Type 2); used to determine warehouse transfer workflow

**Returns:** `Boolean`

---

#### OrderPickRequest {#orderpickrequest}
 `[🔍 get only]`

```4d
Function get OrderPickRequest -> Boolean
```

Returns true if this pick request is for customer orders (Type 0 or 1); used to determine pick request workflow

**Returns:** `Boolean`

---

#### PartsRequested {#partsrequested}
 `[🔍 get only, 🖥️ local]`

```4d
Function get PartsRequested -> Boolean
```

Returns true if any order in pick request has quantity requested (sum > 0); indicates non-empty pick request

**Returns:** `Boolean`

---

#### Picked {#picked}
 `[🔍 get, 🔎 query, 🖥️ local]`

```4d
Function get Picked -> Boolean
Function query Picked($QueryEventObject : Object)
```

Returns true if all items in pick request have been picked (QuantityToPick sum = 0); indicates pick complete

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

Returns true if any items have been picked (QuantityPicked sum > 0); indicates picking has begun

**Returns:** `Boolean`

---

#### Status {#status}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Status -> Text
```

Returns formatted status text with emoji indicating pick request state (Modifying/Ready To Pick/Picking In Progress/Ready To Process/Despatched)

**Returns:** `Text`

---

#### StatusColor {#statuscolor}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StatusColor -> Integer
```

Returns color code for status indicator matching current pick request state

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [PickRequest](../Tables/PickRequest.md) - ORDA Entity class for PickRequest table

### � Related Classes

- [PickRequest](PickRequest.md) - ORDA DataClass class for PickRequest table

### � Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form

---

*Generated from PickRequestEntity.4dm*
