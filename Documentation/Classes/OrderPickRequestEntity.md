---
layout : default
title : OrderPickRequestEntity
parent : Classes
---
# OrderPickRequestEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/OrderPickRequestEntity.4dm)

📊 **Overview:** 2 Functions | 6 Getters | 3 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:07:28.287Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [query Parts](#query parts) (1 param) 🖥️
  - [getPickedStockListboxCollection](#getpickedstocklistboxcollection) → `Collection` 🖥️
  - [QuantityPicked](#quantitypicked) → `Integer`
  - [QuantityToPick](#quantitytopick) → `Integer`
  - [BoxesPerPallet](#boxesperpallet) → `Integer`
  - [Pallets](#pallets) → `Real`
  - [Boxes](#boxes) → `Real`
  - [Parts](#parts) → `Integer`
  - [Pallets](#pallets) (1 param)
  - [Boxes](#boxes) (1 param)
  - [Parts](#parts) (1 param)
- [🔗 Related Items](#related-items)
---

## Functions {#functions}

### Regular Functions

#### query Parts {#query parts}
 `[🖥️ local]`

```4d
Function query Parts($QueryEventObject : Object)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

---

#### getPickedStockListboxCollection {#getpickedstocklistboxcollection}
 `[🖥️ local]`

```4d
Function getPickedStockListboxCollection -> Collection
```

**Returns:** `Collection`

---

### Getters

#### QuantityPicked {#quantitypicked}
 `[🖥️ local, 🔍 getter]`

```4d
Function QuantityPicked -> Integer
```

**Returns:** `Integer`

---

#### QuantityToPick {#quantitytopick}
 `[🖥️ local, 🔍 getter]`

```4d
Function QuantityToPick -> Integer
```

**Returns:** `Integer`

---

#### BoxesPerPallet {#boxesperpallet}
 `[🖥️ local, 🔍 getter]`

```4d
Function BoxesPerPallet -> Integer
```

**Returns:** `Integer`

---

#### Pallets {#pallets}
 `[🖥️ local, 🔍 getter]`

```4d
Function Pallets -> Real
```

MARK:Pallets

**Returns:** `Real`

---

#### Boxes {#boxes}
 `[🖥️ local, 🔍 getter]`

```4d
Function Boxes -> Real
```

MARK:Boxes

**Returns:** `Real`

---

#### Parts {#parts}
 `[🖥️ local, 🔍 getter]`

```4d
Function Parts -> Integer
```

MARK: Parts

**Returns:** `Integer`

---

### Setters

#### Pallets {#pallets}
 `[🖥️ local, ✏️ setter]`

```4d
Function Pallets($Pallets : Real)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Pallets` | `Real` | - | - |

---

#### Boxes {#boxes}
 `[🖥️ local, ✏️ setter]`

```4d
Function Boxes($Boxes : Real)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Boxes` | `Real` | - | - |

---

#### Parts {#parts}
 `[🖥️ local, ✏️ setter]`

```4d
Function Parts($Parts : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parts` | `Integer` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [OrderPickRequest](../Tables/OrderPickRequest.md) - Source table for this ORDA class

### � Related Classes

- [OrderPickRequestSelection](OrderPickRequestSelection.md) - ORDA EntitySelection class for OrderPickRequest table

---

*Generated from OrderPickRequestEntity.4dm*
