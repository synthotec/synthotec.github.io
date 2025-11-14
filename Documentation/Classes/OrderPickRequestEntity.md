---
layout : default
title : OrderPickRequestEntity
parent : Classes
---
# OrderPickRequestEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/OrderPickRequestEntity.4dm)

📊 **Overview:** 1 Functions | 6 Getters | 3 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:53:00.826Z*

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

**Returns:** `Collection`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Boxes {#boxes}
 `[🔍 get, ✏️ set, 🖥️ local]`

```4d
Function get Boxes -> Real
Function set Boxes($Boxes : Real)
```

MARK:Boxes

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

**Returns:** `Integer`

---

#### Pallets {#pallets}
 `[🔍 get, ✏️ set, 🖥️ local]`

```4d
Function get Pallets -> Real
Function set Pallets($Pallets : Real)
```

MARK:Pallets

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

MARK: Parts

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

**Returns:** `Integer`

---

#### QuantityToPick {#quantitytopick}
 `[🔍 get only, 🖥️ local]`

```4d
Function get QuantityToPick -> Integer
```

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [OrderPickRequest](../Tables/OrderPickRequest.md) - Source table for this ORDA class

### � Related Classes

- [OrderPickRequestSelection](OrderPickRequestSelection.md) - ORDA EntitySelection class for OrderPickRequest table

---

*Generated from OrderPickRequestEntity.4dm*
