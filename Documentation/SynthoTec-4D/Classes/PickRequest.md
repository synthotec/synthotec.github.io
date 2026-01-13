---
layout : default
title : PickRequest
parent : Classes
---
# PickRequest [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PickRequest.4dm)

📊 **Overview:** 11 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:12.505Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [create](#create) → `$PickRequestEntity : cs.PickRequestEntity` 🖥️
    - [newUsingEntry](#newusingentry) → `$PickRequestEntity : cs.PickRequestEntity` 🖥️
    - [getOpenRequests](#getopenrequests) → `cs.PickRequestSelection` 🖥️
    - [restInitialPage](#restinitialpage) (1 param) → `Object`
    - [restPickPage](#restpickpage) (1 param) → `Object`
    - [restUnpickStock](#restunpickstock) (1 param) → `Object`
    - [restViewStock](#restviewstock) (1 param) → `Object`
    - [restScanStock](#restscanstock) (1 param) → `Object`
    - [restSelectOrderToPickAgainst](#restselectordertopickagainst) (1 param) → `Object`
    - [restPickAgainstOrder](#restpickagainstorder) (1 param) → `Object`
    - [checkForPickedPickRequests](#checkforpickedpickrequests)
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### create {#create}
 `[🖥️ local]`

```4d
Function create -> $PickRequestEntity : cs.PickRequestEntity
```

Opens modify dialog for new pick request; returns created entity if saved, null if cancelled

**Returns:** `cs.PickRequestEntity`

---

#### newUsingEntry {#newusingentry}
 `[🖥️ local]`

```4d
Function newUsingEntry -> $PickRequestEntity : cs.PickRequestEntity
```

Opens UI entry dialog to create new pick request with customer and despatch date; returns created entity if saved, null if cancelled

**Returns:** `cs.PickRequestEntity`

---

#### getOpenRequests {#getopenrequests}
 `[🖥️ local]`

```4d
Function getOpenRequests -> cs.PickRequestSelection
```

Returns all pick requests; used to filter ready-to-pick requests in REST API

**Returns:** `cs.PickRequestSelection`

---

#### restInitialPage {#restinitialpage}


```4d
Function restInitialPage($RestPostDataObject : Object) -> Object
```

REST endpoint for mobile warehouse app; returns view with list of open pick requests ready to pick, styled as clickable buttons

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restPickPage {#restpickpage}


```4d
Function restPickPage($RestPostDataObject : Object) -> Object
```

REST endpoint showing specific pick request with orders to pick; displays UI for stock picking with box quantity input and order details

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restUnpickStock {#restunpickstock}


```4d
Function restUnpickStock($RestPostDataObject : Object) -> Object
```

REST endpoint to reverse picked stock; returns confirmation view after unpicking boxes from pick request

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restViewStock {#restviewstock}


```4d
Function restViewStock($RestPostDataObject : Object) -> Object
```

REST endpoint showing current stock availability for orders in pick request; displays works order details with available/finished stock and bin locations

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restScanStock {#restscanstock}


```4d
Function restScanStock($RestPostDataObject : Object) -> Object
```

REST endpoint for mobile barcode scanning; accepts box/pallet scans and updates picked quantities in pick request; returns updated view with scan results

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restSelectOrderToPickAgainst {#restselectordertopickagainst}


```4d
Function restSelectOrderToPickAgainst($RestPostDataObject : Object) -> Object
```

REST endpoint showing available customer orders that can be added to pick request; returns filtered list of non-completed orders for selection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restPickAgainstOrder {#restpickagainstorder}


```4d
Function restPickAgainstOrder($RestPostDataObject : Object) -> Object
```

REST endpoint to add selected customer order to pick request; links order's stock to pick request and returns updated picking view

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### checkForPickedPickRequests {#checkforpickedpickrequests}


```4d
Function checkForPickedPickRequests
```

Monitors for pick requests that have finished picking and automatically triggers despatch workflow and notifications

---

## Related Items {#related-items}

### 🗂️ Tables

- [PickRequest](../Tables/PickRequest.md) - ORDA DataClass class for PickRequest table

### � Related Classes

- [PickRequestEntity](PickRequestEntity.md) - ORDA Entity class for PickRequest table

### � Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form

---

*Generated from PickRequest.4dm*
