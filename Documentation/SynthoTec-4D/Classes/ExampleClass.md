---
layout : default
title : ExampleClass
parent : Classes
---
# ExampleClass [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ExampleClass.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions | 1 Getters

## 📝 Description

🗨️ Example class to demonstrate inline comments and parameter documentation

🕐 *Last updated: 2025-11-19T15:47:08.230Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [calculateValue](#calculatevalue) (1 param) → `Real`
    - [processOrder](#processorder) (2 params) → `Boolean`
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [ItemCount](#itemcount) 🔍 → `Integer`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Title` | `Text` | - | The title of the item |
| `Count` | `Integer` | `0` | Number of items in stock |

## Constructor {#constructor}

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

## Functions {#functions}

### Regular Functions

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

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### ItemCount {#itemcount}
 `[🔍 get only]`

```4d
Function get ItemCount -> Integer
```

**Returns:** `Integer`

---

---

*Generated from ExampleClass.4dm*
