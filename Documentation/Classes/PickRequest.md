---
layout : default
title : PickRequest
parent : Classes
---
# PickRequest

📊 **Overview:** 11 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T02:24:48.485Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (11):**

- [create](#create) → `cs.PickRequestEntity` 🖥️
- [newUsingEntry](#newusingentry) → `cs.PickRequestEntity` 🖥️
- [getOpenRequests](#getopenrequests) → `cs.PickRequestSelection` 🖥️
- [restInitialPage](#restinitialpage) (1 param) → `Object`
- [restPickPage](#restpickpage) (1 param) → `Object`
- [restUnpickStock](#restunpickstock) (1 param) → `Object`
- [restViewStock](#restviewstock) (1 param) → `Object`
- [restScanStock](#restscanstock) (1 param) → `Object`
- [restSelectOrderToPickAgainst](#restselectordertopickagainst) (1 param) → `Object`
- [restPickAgainstOrder](#restpickagainstorder) (1 param) → `Object`
- [checkForPickedPickRequests](#checkforpickedpickrequests)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### create {#create}
 `[🖥️ local]`

```4d
Function create -> cs.PickRequestEntity
```

**Returns:** `cs.PickRequestEntity`

---

#### newUsingEntry {#newusingentry}
 `[🖥️ local]`

```4d
Function newUsingEntry -> cs.PickRequestEntity
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

---

*Generated from PickRequest.4dm*
