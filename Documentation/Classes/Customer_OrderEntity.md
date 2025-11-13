---
layout : default
title : Customer_OrderEntity
parent : Classes
---
# Customer_OrderEntity

📊 **Overview:** 9 Functions | 6 Getters | 1 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T13:29:02.452Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (9):**

- [createCofC](#createcofc) (3 params) → `cs.CofCEntity` 🖥️
- [getAvailableForPickRequest](#getavailableforpickrequest) (1 param) → `Integer` 🖥️
- [modifyOrderPickRequest](#modifyorderpickrequest) (1 param) → `cs.OrderPickRequestEntity` 🖥️
- [getPickRequestedQuantity](#getpickrequestedquantity) (1 param) → `Integer` 🖥️
- [getPickedQuantity](#getpickedquantity) (1 param) → `Integer` 🖥️
- [getPickedQuantitiesColor](#getpickedquantitiescolor) → `Integer` 🖥️
- [getPickedQuantitiesText](#getpickedquantitiestext) (1 param) → `Text` 🖥️
- [getPickRequestQuantitiesText](#getpickrequestquantitiestext) (1 param) → `Text` 🖥️
- [getPickRequestQuantitiesColor](#getpickrequestquantitiescolor) → `Integer` 🖥️

**🔍 Getters (6):**

- [DespatchDateTime](#despatchdatetime) → `cs.System.DateTime`
- [DeliveryDateTime](#deliverydatetime) → `cs.System.DateTime`
- [DespatchDate](#despatchdate) → `Date`
- [DeliveryDate](#deliverydate) → `Date`
- [OutstandingToDeliver](#outstandingtodeliver) → `Integer`
- [OutstandingToPickRequest](#outstandingtopickrequest) → `Integer`

**✏️ Setters (1):**

- [OutstandingToDeliver](#outstandingtodeliver) (1 param)

### 🔗 Related Items

- [Tables](#-tables) (1)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### createCofC {#createcofc}
 `[🖥️ local]`

```4d
Function createCofC($Advice_NoteEntity : cs.Advice_NoteEntity; $WorksOrderEntity : cs.WorksOrderEntity; $Quantity : Integer) -> cs.CofCEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Advice_NoteEntity` | `cs.Advice_NoteEntity` | - | - |
| `$WorksOrderEntity` | `cs.WorksOrderEntity` | - | - |
| `$Quantity` | `Integer` | - | - |

**Returns:** `cs.CofCEntity`

---

#### getAvailableForPickRequest {#getavailableforpickrequest}
 `[🖥️ local]`

```4d
Function getAvailableForPickRequest($PickRequestEntity : cs.PickRequestEntity) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |

**Returns:** `Integer`

---

#### modifyOrderPickRequest {#modifyorderpickrequest}
 `[🖥️ local]`

```4d
Function modifyOrderPickRequest($PickRequestEntity : cs.PickRequestEntity) -> cs.OrderPickRequestEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |

**Returns:** `cs.OrderPickRequestEntity`

---

#### getPickRequestedQuantity {#getpickrequestedquantity}
 `[🖥️ local]`

```4d
Function getPickRequestedQuantity($PickRequestEntity : cs.PickRequestEntity) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |

**Returns:** `Integer`

---

#### getPickedQuantity {#getpickedquantity}
 `[🖥️ local]`

```4d
Function getPickedQuantity($PickRequestEntity : cs.PickRequestEntity) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |

**Returns:** `Integer`

---

#### getPickedQuantitiesColor {#getpickedquantitiescolor}
 `[🖥️ local]`

```4d
Function getPickedQuantitiesColor -> Integer
```

**Returns:** `Integer`

---

#### getPickedQuantitiesText {#getpickedquantitiestext}
 `[🖥️ local]`

```4d
Function getPickedQuantitiesText($PickRequestEntity : cs.PickRequestEntity) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |

**Returns:** `Text`

---

#### getPickRequestQuantitiesText {#getpickrequestquantitiestext}
 `[🖥️ local]`

```4d
Function getPickRequestQuantitiesText($PickRequestEntity : cs.PickRequestEntity) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |

**Returns:** `Text`

---

#### getPickRequestQuantitiesColor {#getpickrequestquantitiescolor}
 `[🖥️ local]`

```4d
Function getPickRequestQuantitiesColor -> Integer
```

**Returns:** `Integer`

---

### 🔍 Getters

#### DespatchDateTime {#despatchdatetime}
 `[🖥️ local, 🔍 getter]`

```4d
Function DespatchDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

#### DeliveryDateTime {#deliverydatetime}
 `[🖥️ local, 🔍 getter]`

```4d
Function DeliveryDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

#### DespatchDate {#despatchdate}
 `[🖥️ local, 🔍 getter]`

```4d
Function DespatchDate -> Date
```

**Returns:** `Date`

---

#### DeliveryDate {#deliverydate}
 `[🖥️ local, 🔍 getter]`

```4d
Function DeliveryDate -> Date
```

**Returns:** `Date`

---

#### OutstandingToDeliver {#outstandingtodeliver}
 `[🖥️ local, 🔍 getter]`

```4d
Function OutstandingToDeliver -> Integer
```

**Returns:** `Integer`

---

#### OutstandingToPickRequest {#outstandingtopickrequest}
 `[🖥️ local, 🔍 getter]`

```4d
Function OutstandingToPickRequest -> Integer
```

**Returns:** `Integer`

---

### ✏️ Setters

#### OutstandingToDeliver {#outstandingtodeliver}
 `[🖥️ local, ✏️ setter]`

```4d
Function OutstandingToDeliver($OutstandingToDeliver : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$OutstandingToDeliver` | `Integer` | - | - |

---

## 🔗 Related Items

### 🗂️ Tables

- [Customer_Order](../Tables/Customer_Order.md) - Entity class

---

*Generated from Customer_OrderEntity.4dm*
