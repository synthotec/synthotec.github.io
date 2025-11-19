---
layout : default
title : ProcurementProgramLine
parent : Classes
---
# ProcurementProgramLine [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProcurementProgramLine.4dm)

📊 **Overview:** 18 Properties | 1 Constructor | 14 Functions | 13 Getters

## 📝 Description

🗨️ $Column.BackgroundColor:=Color.PastelGreen

🕐 *Last updated: 2025-11-19T18:12:03.471Z*

---

## 📑 Table of Contents

- [📋 Properties (18)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setDefaultActions](#setdefaultactions)
    - [newFromText](#newfromtext) (1 param)
    - [newFromCustomerOrder](#newfromcustomerorder) (1 param)
    - [getWarehouseWithCustomerCode](#getwarehousewithcustomercode) → `Text`
    - [setAction](#setaction)
    - [_setActions](#_setactions) (1 param)
    - [_copyItemNumber](#_copyitemnumber)
    - [_setActionIgnore](#_setactionignore) (1 param)
    - [process](#process)
    - [_setNewCustomer_OrderEntity](#_setnewcustomer_orderentity) → `$Customer_OrderEntity : cs.Customer_OrderEntity`
    - [process_CreateForecast](#process_createforecast)
    - [process_CreateOrder](#process_createorder)
    - [process_UpdateOrder](#process_updateorder)
    - [process_CloseOrder](#process_closeorder)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [ActionText->$ActionText](#actiontext->$actiontext) 🔍 → `Text`
    - [IsActionSet](#isactionset) 🔍 → `Boolean`
    - [IsBacklog](#isbacklog) 🔍 → `Boolean`
    - [IsExistingOrder](#isexistingorder) 🔍 → `Boolean`
    - [IsExistingOrderModified](#isexistingordermodified) 🔍 → `Boolean`
    - [IsForecast](#isforecast) 🔍 → `Boolean`
    - [IsItemMissing](#isitemmissing) 🔍 → `Boolean`
    - [IsNewOrder](#isneworder) 🔍 → `Boolean`
    - [Meta->$Meta](#meta->$meta) 🔍 → `cs.UI.ListBoxMeta`
    - [OrderBatchNumber](#orderbatchnumber) 🔍 → `Text`
    - [OurPartName](#ourpartname) 🔍 → `Text`
    - [StatusText->$StatusText](#statustext->$statustext) 🔍 → `Text`
    - [WeekNumberText](#weeknumbertext) 🔍 → `Text`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `ItemNumber` | `Text` | - | - |
| `OrderNumber` | `Text` | - | - |
| `Quantity` | `Integer` | - | - |
| `DueDate` | `Date` | - | - |
| `ItemDescription` | `Text` | - | - |
| `Vmi` | `Boolean` | - | - |
| `Warehouse` | `Text` | - | - |
| `Product_OptionEntity` | `cs.Product_OptionEntity` | - | - |
| `Customer_OrderEntity` | `cs.Customer_OrderEntity` | - | - |
| `ProcurementProgram` | `cs.ProcurementProgram` | - | - |
| `RemovedFromProgram` | `Boolean` | - | - |
| `Action_CreateForecast` | `Boolean` | - | - |
| `Action_CreateOrder` | `Boolean` | - | - |
| `Action_Ignore` | `Boolean` | - | - |
| `Action_CloseOrder` | `Boolean` | - | - |
| `Action_UpdateOrder` | `Boolean` | - | - |
| `WarehouseWithCustomerCode` | `Text` | - | - |
| `ds` | *Not specified* | `DataStore(0)` | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($TextLineOrCustomer_OrderEntity : Variant; $ProcurementProgram : cs.ProcurementProgram)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TextLineOrCustomer_OrderEntity` | `Variant` | - | - |
| `$ProcurementProgram` | `cs.ProcurementProgram` | - | - |

---

## Functions {#functions}

### Regular Functions

#### setDefaultActions {#setdefaultactions}


```4d
Function setDefaultActions
```

---

#### newFromText {#newfromtext}


```4d
Function newFromText($Line : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Line` | `Text` | - | - |

---

#### newFromCustomerOrder {#newfromcustomerorder}


```4d
Function newFromCustomerOrder($Customer_OrderEntity : cs.Customer_OrderEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Customer_OrderEntity` | `cs.Customer_OrderEntity` | - | - |

---

#### getWarehouseWithCustomerCode {#getwarehousewithcustomercode}


```4d
Function getWarehouseWithCustomerCode -> Text
```

**Returns:** `Text`

---

#### setAction {#setaction}


```4d
Function setAction
```

---

#### _setActions {#_setactions}


```4d
Function _setActions($ActiveActionProperty : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ActiveActionProperty` | `Text` | - | - |

---

#### _copyItemNumber {#_copyitemnumber}


```4d
Function _copyItemNumber
```

---

#### _setActionIgnore {#_setactionignore}


```4d
Function _setActionIgnore($IgnoreForAllOrders : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$IgnoreForAllOrders` | `Boolean` | - | - |

---

#### process {#process}


```4d
Function process
```

---

#### _setNewCustomer_OrderEntity {#_setnewcustomer_orderentity}


```4d
Function _setNewCustomer_OrderEntity -> $Customer_OrderEntity : cs.Customer_OrderEntity
```

**Returns:** `cs.Customer_OrderEntity`

---

#### process_CreateForecast {#process_createforecast}


```4d
Function process_CreateForecast
```

---

#### process_CreateOrder {#process_createorder}


```4d
Function process_CreateOrder
```

---

#### process_UpdateOrder {#process_updateorder}


```4d
Function process_UpdateOrder
```

---

#### process_CloseOrder {#process_closeorder}


```4d
Function process_CloseOrder
```

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### ActionText->$ActionText {#actiontext->$actiontext}
 `[🔍 get only]`

```4d
Function get ActionText->$ActionText -> Text
```

**Returns:** `Text`

---

#### IsActionSet {#isactionset}
 `[🔍 get only]`

```4d
Function get IsActionSet -> Boolean
```

**Returns:** `Boolean`

---

#### IsBacklog {#isbacklog}
 `[🔍 get only]`

```4d
Function get IsBacklog -> Boolean
```

**Returns:** `Boolean`

---

#### IsExistingOrder {#isexistingorder}
 `[🔍 get only]`

```4d
Function get IsExistingOrder -> Boolean
```

**Returns:** `Boolean`

---

#### IsExistingOrderModified {#isexistingordermodified}
 `[🔍 get only]`

```4d
Function get IsExistingOrderModified -> Boolean
```

**Returns:** `Boolean`

---

#### IsForecast {#isforecast}
 `[🔍 get only]`

```4d
Function get IsForecast -> Boolean
```

**Returns:** `Boolean`

---

#### IsItemMissing {#isitemmissing}
 `[🔍 get only]`

```4d
Function get IsItemMissing -> Boolean
```

**Returns:** `Boolean`

---

#### IsNewOrder {#isneworder}
 `[🔍 get only]`

```4d
Function get IsNewOrder -> Boolean
```

**Returns:** `Boolean`

---

#### Meta->$Meta {#meta->$meta}
 `[🔍 get only]`

```4d
Function get Meta->$Meta -> cs.UI.ListBoxMeta
```

**Returns:** `cs.UI.ListBoxMeta`

---

#### OrderBatchNumber {#orderbatchnumber}
 `[🔍 get only]`

```4d
Function get OrderBatchNumber -> Text
```

**Returns:** `Text`

---

#### OurPartName {#ourpartname}
 `[🔍 get only]`

```4d
Function get OurPartName -> Text
```

**Returns:** `Text`

---

#### StatusText->$StatusText {#statustext->$statustext}
 `[🔍 get only]`

```4d
Function get StatusText->$StatusText -> Text
```

**Returns:** `Text`

---

#### WeekNumberText {#weeknumbertext}
 `[🔍 get only]`

```4d
Function get WeekNumberText -> Text
```

**Returns:** `Text`

---

---

*Generated from ProcurementProgramLine.4dm*
