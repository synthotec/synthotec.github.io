# Customer_OrderEntity

**Extends:** `Entity`

## Table of Contents

### Functions

- [DespatchDateTime() [getter]](#despatchdatetime)
- [DeliveryDateTime() [getter]](#deliverydatetime)
- [DespatchDate() [getter]](#despatchdate)
- [DeliveryDate() [getter]](#deliverydate)
- [createCofC()](#createcofc)
- [getAvailableForPickRequest()](#getavailableforpickrequest)
- [OutstandingToDeliver() [getter]](#outstandingtodeliver)
- [OutstandingToDeliver() [setter]](#outstandingtodeliver)
- [OutstandingToPickRequest() [getter]](#outstandingtopickrequest)
- [modifyOrderPickRequest()](#modifyorderpickrequest)
- [getPickRequestedQuantity()](#getpickrequestedquantity)
- [getPickedQuantity()](#getpickedquantity)
- [getPickedQuantitiesColor()](#getpickedquantitiescolor)
- [getPickedQuantitiesText()](#getpickedquantitiestext)
- [getPickRequestQuantitiesText()](#getpickrequestquantitiestext)
- [getPickRequestQuantitiesColor()](#getpickrequestquantitiescolor)

---

## Functions

### DespatchDateTime {#despatchdatetime}
 `[local]` `[getter]`

```4d
Function DespatchDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

### DeliveryDateTime {#deliverydatetime}
 `[local]` `[getter]`

```4d
Function DeliveryDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

### DespatchDate {#despatchdate}
 `[local]` `[getter]`

```4d
Function DespatchDate -> Date
```

**Returns:** `Date`

---

### DeliveryDate {#deliverydate}
 `[local]` `[getter]`

```4d
Function DeliveryDate -> Date
```

**Returns:** `Date`

---

### createCofC {#createcofc}
 `[local]`

```4d
Function createCofC($Advice_NoteEntity : cs.Advice_NoteEntity; $WorksOrderEntity : cs.WorksOrderEntity; $Quantity : Integer) -> cs.CofCEntity
```

**Returns:** `cs.CofCEntity`

---

### getAvailableForPickRequest {#getavailableforpickrequest}
 `[local]`

```4d
Function getAvailableForPickRequest($PickRequestEntity : cs.PickRequestEntity) -> Integer
```

**Returns:** `Integer`

---

### OutstandingToDeliver {#outstandingtodeliver}
 `[local]` `[getter]`

```4d
Function OutstandingToDeliver -> Integer
```

**Returns:** `Integer`

---

### OutstandingToDeliver {#outstandingtodeliver}
 `[local]` `[setter]`

```4d
Function OutstandingToDeliver($OutstandingToDeliver : Integer)
```

---

### OutstandingToPickRequest {#outstandingtopickrequest}
 `[local]` `[getter]`

```4d
Function OutstandingToPickRequest -> Integer
```

**Returns:** `Integer`

---

### modifyOrderPickRequest {#modifyorderpickrequest}
 `[local]`

```4d
Function modifyOrderPickRequest($PickRequestEntity : cs.PickRequestEntity) -> cs.OrderPickRequestEntity
```

**Returns:** `cs.OrderPickRequestEntity`

---

### getPickRequestedQuantity {#getpickrequestedquantity}
 `[local]`

```4d
Function getPickRequestedQuantity($PickRequestEntity : cs.PickRequestEntity) -> Integer
```

**Returns:** `Integer`

---

### getPickedQuantity {#getpickedquantity}
 `[local]`

```4d
Function getPickedQuantity($PickRequestEntity : cs.PickRequestEntity) -> Integer
```

**Returns:** `Integer`

---

### getPickedQuantitiesColor {#getpickedquantitiescolor}
 `[local]`

```4d
Function getPickedQuantitiesColor -> Integer
```

**Returns:** `Integer`

---

### getPickedQuantitiesText {#getpickedquantitiestext}
 `[local]`

```4d
Function getPickedQuantitiesText($PickRequestEntity : cs.PickRequestEntity) -> Text
```

**Returns:** `Text`

---

### getPickRequestQuantitiesText {#getpickrequestquantitiestext}
 `[local]`

```4d
Function getPickRequestQuantitiesText($PickRequestEntity : cs.PickRequestEntity) -> Text
```

**Returns:** `Text`

---

### getPickRequestQuantitiesColor {#getpickrequestquantitiescolor}
 `[local]`

```4d
Function getPickRequestQuantitiesColor -> Integer
```

**Returns:** `Integer`

---

---

*Generated from Customer_OrderEntity.4dm*
*Last updated: 2025-11-12T17:04:21.515Z*
