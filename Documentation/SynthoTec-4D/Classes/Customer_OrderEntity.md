---
layout : default
title : Customer_OrderEntity
parent : Classes
---
# Customer_OrderEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer_OrderEntity.4dm)

📊 **Overview:** 9 Functions | 6 Getters | 1 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T21:53:02.250Z*

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

- [Customer_Order](../Tables/Customer_Order.md) - ORDA Entity class for Customer_Order table

### � Related Classes

- [Customer_Order](Customer_Order.md) - ORDA DataClass class for Customer_Order table

### � Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [ConfirmOrderDates](../Forms/ConfirmOrderDates.md) - Data source for ConfirmOrderDates form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [PackingListGenerator](../Forms/PackingListGenerator.md) - Data source for PackingListGenerator form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form
- [PriceChangeOrders](../Forms/PriceChangeOrders.md) - Data source for PriceChangeOrders form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form
- [Schedule_Variables](../Forms/Schedule_Variables.md) - Data source for Schedule_Variables form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form

---

*Generated from Customer_OrderEntity.4dm*
