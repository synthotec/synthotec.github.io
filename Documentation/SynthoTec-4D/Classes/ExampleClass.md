---
layout : default
title : ExampleClass
parent : Classes
---
# ExampleClass [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ExampleClass.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions | 1 Getters

## 📝 Description

Creates example object with initial inventory count

🕐 *Last updated: 2025-11-20T14:23:48.920Z*

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

Creates example object with initial inventory count

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

Calculates total inventory value by multiplying count by unit price

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

Processes order by reducing count if sufficient quantity available, returns success status

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

Returns the current item count

**Returns:** `Integer`

---

---

*Generated from ExampleClass.4dm*
