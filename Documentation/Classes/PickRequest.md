---
layout : default
title : PickRequest
parent : Classes
---
# PickRequest [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PickRequest.4dm)

📊 **Overview:** 11 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T16:35:58.973Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
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

**Returns:** `cs.PickRequestEntity`

---

#### newUsingEntry {#newusingentry}
 `[🖥️ local]`

```4d
Function newUsingEntry -> $PickRequestEntity : cs.PickRequestEntity
```

**Returns:** `cs.PickRequestEntity`

---

#### getOpenRequests {#getopenrequests}
 `[🖥️ local]`

```4d
Function getOpenRequests -> cs.PickRequestSelection
```

**Returns:** `cs.PickRequestSelection`

---

#### restInitialPage {#restinitialpage}


```4d
Function restInitialPage($RestPostDataObject : Object) -> Object
```

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

---

## Related Items {#related-items}

### 🗂️ Tables

- [PickRequest](../Tables/PickRequest.md) - Source table for this ORDA class

### � Related Classes

- [PickRequestEntity](PickRequestEntity.md) - ORDA Entity class for PickRequest table

---

*Generated from PickRequest.4dm*
