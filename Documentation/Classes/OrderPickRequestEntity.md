---
layout : default
title : OrderPickRequestEntity
parent : Classes
---
# OrderPickRequestEntity

📊 **Overview:** 2 Functions | 6 Getters | 3 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T16:35:14.823Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [query Parts](#query parts) (1 param) 🖥️
- [getPickedStockListboxCollection](#getpickedstocklistboxcollection) → `Collection` 🖥️

**🔍 Getters (6):**

- [QuantityPicked](#quantitypicked) → `Integer`
- [QuantityToPick](#quantitytopick) → `Integer`
- [BoxesPerPallet](#boxesperpallet) → `Integer`
- [Pallets](#pallets) → `Real`
- [Boxes](#boxes) → `Real`
- [Parts](#parts) → `Integer`

**✏️ Setters (3):**

- [Pallets](#pallets) (1 param)
- [Boxes](#boxes) (1 param)
- [Parts](#parts) (1 param)

### 🔗 Related Items

- [Tables](#️-tables) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

### 🔍 Getters

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

### ✏️ Setters

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

## 🔗 Related Items

### 🗂️ Tables

- [OrderPickRequest](../Tables/OrderPickRequest.md) - Source table

---

*Generated from OrderPickRequestEntity.4dm*
