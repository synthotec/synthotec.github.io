---
layout : default
title : OrderPickRequestEntity
parent : Classes
---
# OrderPickRequestEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/OrderPickRequestEntity.4dm)

📊 **Overview:** 1 Functions | 6 Getters | 3 Setters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:12.209Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getPickedStockListboxCollection](#getpickedstocklistboxcollection) → `Collection` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Boxes](#boxes) 🔍 ✏️ → `Real`
    - [BoxesPerPallet](#boxesperpallet) 🔍 → `Integer`
    - [Pallets](#pallets) 🔍 ✏️ → `Real`
    - [Parts](#parts) 🔍 ✏️ 🔎 → `Integer`
    - [QuantityPicked](#quantitypicked) 🔍 → `Integer`
    - [QuantityToPick](#quantitytopick) 🔍 → `Integer`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getPickedStockListboxCollection {#getpickedstocklistboxcollection}
 `[🖥️ local]`

```4d
Function getPickedStockListboxCollection -> Collection
```

Returns collection of picked stock items for listbox display; includes pallets and individual boxes with works order and quantities

**Returns:** `Collection`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Boxes {#boxes}
 `[🔍 get, ✏️ set, 🖥️ local]`

```4d
Function get Boxes -> Real
Function set Boxes($Boxes : Real)
```

Returns number of boxes calculated by dividing parts by items per box from product; returns 0 if no items per box

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Boxes` | `Real` | - |

**Returns:** `Real`

---

#### BoxesPerPallet {#boxesperpallet}
 `[🔍 get only, 🖥️ local]`

```4d
Function get BoxesPerPallet -> Integer
```

Returns boxes per pallet from customer or product's pallet method; fallback to 0 if not defined

**Returns:** `Integer`

---

#### Pallets {#pallets}
 `[🔍 get, ✏️ set, 🖥️ local]`

```4d
Function get Pallets -> Real
Function set Pallets($Pallets : Real)
```

Returns number of pallets calculated by dividing boxes by boxes per pallet; returns 0 if boxes per pallet is 0

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Pallets` | `Real` | - |

**Returns:** `Real`

---

#### Parts {#parts}
 `[🔍 get, ✏️ set, 🔎 query, 🖥️ local]`

```4d
Function get Parts -> Integer
Function set Parts($Parts : Integer)
Function query Parts($QueryEventObject : Object)
```

Returns the quantity property (alias for inventory quantity in pick request)

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Parts` | `Integer` | - |

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

**Returns:** `Integer`

---

#### QuantityPicked {#quantitypicked}
 `[🔍 get only, 🖥️ local]`

```4d
Function get QuantityPicked -> Integer
```

Returns total quantity already picked (boxes + pallets of boxes) from all BoxLabels and Pallet selections

**Returns:** `Integer`

---

#### QuantityToPick {#quantitytopick}
 `[🔍 get only, 🖥️ local]`

```4d
Function get QuantityToPick -> Integer
```

Returns remaining quantity to pick (total quantity minus quantity already picked)

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [OrderPickRequest](../Tables/OrderPickRequest.md) - ORDA Entity class for OrderPickRequest table

### � Related Classes

- [OrderPickRequestSelection](OrderPickRequestSelection.md) - ORDA EntitySelection class for OrderPickRequest table

### � Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form

---

*Generated from OrderPickRequestEntity.4dm*
