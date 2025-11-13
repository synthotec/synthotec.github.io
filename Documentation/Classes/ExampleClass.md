---
layout : default
title : ExampleClass
parent : Classes
---
# ExampleClass

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions | 1 Getters

## 📝 Description

🗨️ Example class to demonstrate inline comments and parameter documentation

🕐 *Last updated: 2025-11-13T01:17:23.176Z*

---

## 📑 Table of Contents

### 📋 Properties (2)

- [Title](#title) : `Text`
- [Count](#count) : `Integer`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Functions (2):**

- [calculateValue](#calculatevalue) (1 param) → `Real`
- [processOrder](#processorder) (2 params) → `Boolean`

**🔍 Getters (1):**

- [ItemCount](#itemcount) → `Integer`

---

## 📋 Properties

### Quick Reference

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Title` | `Text` | - | The title of the item |
| `Count` | `Integer` | `0` | Number of items in stock |

### Detailed Information

#### Title {#title}

**Type:** `Text`

The title of the item

---

#### Count {#count}

**Type:** `Integer`

**Default Value:** `0`

Number of items in stock

---

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($InitialCount : Integer)
```

$InitialCount: Starting inventory count

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$InitialCount` | `Integer` | - | - |

---

### ⚙️ Regular Functions

#### calculateValue {#calculatevalue}


```4d
Function calculateValue($UnitPrice : Real) -> Real
```

Returns total inventory value

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$UnitPrice` | `Real` | - | - |

**Returns:** `Real`

---

#### processOrder {#processorder}


```4d
Function processOrder($Quantity : Integer; $DiscountPercent : Real) -> Boolean
```

$Quantity: Number of items to order

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Quantity` | `Integer` | - | - |
| `$DiscountPercent` | `Real` | - | - |

**Returns:** `Boolean`

---

### 🔍 Getters

#### ItemCount {#itemcount}
 `[🔍 getter]`

```4d
Function ItemCount -> Integer
```

**Returns:** `Integer`

---

---

*Generated from ExampleClass.4dm*
