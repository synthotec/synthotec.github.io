---
layout : default
title : Customer_OrderEntity
parent : Classes
---
# Customer_OrderEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer_OrderEntity.4dm)

📊 **Overview:** 9 Functions | 6 Getters | 1 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T15:47:07.973Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [createCofC](#createcofc) (3 params) → `$CofCEntity : cs.CofCEntity` 🖥️
    - [getAvailableForPickRequest](#getavailableforpickrequest) (1 param) → `$AvailableForPickRequest : Integer` 🖥️
    - [modifyOrderPickRequest](#modifyorderpickrequest) (1 param) → `$OrderPickRequestEntity : cs.OrderPickRequestEntity` 🖥️
    - [getPickRequestedQuantity](#getpickrequestedquantity) (1 param) → `Integer` 🖥️
    - [getPickedQuantity](#getpickedquantity) (1 param) → `Integer` 🖥️
    - [getPickedQuantitiesColor](#getpickedquantitiescolor) → `Integer` 🖥️
    - [getPickedQuantitiesText](#getpickedquantitiestext) (1 param) → `Text` 🖥️
    - [getPickRequestQuantitiesText](#getpickrequestquantitiestext) (1 param) → `Text` 🖥️
    - [getPickRequestQuantitiesColor](#getpickrequestquantitiescolor) → `Integer` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [DeliveryDate](#deliverydate) 🔍 → `Date`
    - [DeliveryDateTime](#deliverydatetime) 🔍 → `cs.System.DateTime`
    - [DespatchDate](#despatchdate) 🔍 → `Date`
    - [DespatchDateTime](#despatchdatetime) 🔍 → `cs.System.DateTime`
    - [OutstandingToDeliver](#outstandingtodeliver) 🔍 ✏️ → `Integer`
    - [OutstandingToPickRequest](#outstandingtopickrequest) 🔍 → `Integer`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### createCofC {#createcofc}
 `[🖥️ local]`

```4d
Function createCofC($Advice_NoteEntity : cs.Advice_NoteEntity; $WorksOrderEntity : cs.WorksOrderEntity; $Quantity : Integer) -> $CofCEntity : cs.CofCEntity
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
Function getAvailableForPickRequest($PickRequestEntity : cs.PickRequestEntity) -> $AvailableForPickRequest : Integer
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
Function modifyOrderPickRequest($PickRequestEntity : cs.PickRequestEntity) -> $OrderPickRequestEntity : cs.OrderPickRequestEntity
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

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### DeliveryDate {#deliverydate}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DeliveryDate -> Date
```

**Returns:** `Date`

---

#### DeliveryDateTime {#deliverydatetime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DeliveryDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

#### DespatchDate {#despatchdate}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DespatchDate -> Date
```

**Returns:** `Date`

---

#### DespatchDateTime {#despatchdatetime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DespatchDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

#### OutstandingToDeliver {#outstandingtodeliver}
 `[🔍 get, ✏️ set, 🖥️ local]`

```4d
Function get OutstandingToDeliver -> Integer
Function set OutstandingToDeliver($OutstandingToDeliver : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$OutstandingToDeliver` | `Integer` | - |

**Returns:** `Integer`

---

#### OutstandingToPickRequest {#outstandingtopickrequest}
 `[🔍 get only, 🖥️ local]`

```4d
Function get OutstandingToPickRequest -> Integer
```

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Customer_Order](../Tables/Customer_Order.md) - Source table for this ORDA class

---

*Generated from Customer_OrderEntity.4dm*
