---
layout : default
title : ProcurementProgramLine
parent : Classes
---
# ProcurementProgramLine

📊 **Overview:** 18 Properties | 1 Constructor | 14 Functions | 13 Getters

## 📝 Description

🗨️ $Column.BackgroundColor:=Color.PastelGreen

🕐 *Last updated: 2025-11-13T13:39:36.290Z*

---

## 📑 Table of Contents

### 📋 Properties (18)

- [ItemNumber](#itemnumber) : `Text`
- [OrderNumber](#ordernumber) : `Text`
- [Quantity](#quantity) : `Integer`
- [DueDate](#duedate) : `Date`
- [ItemDescription](#itemdescription) : `Text`
- [Vmi](#vmi) : `Boolean`
- [Warehouse](#warehouse) : `Text`
- [Product_OptionEntity](#productoptionentity) : `cs.Product_OptionEntity`
- [Customer_OrderEntity](#customerorderentity) : `cs.Customer_OrderEntity`
- [ProcurementProgram](#procurementprogram) : `cs.ProcurementProgram`
- [RemovedFromProgram](#removedfromprogram) : `Boolean`
- [Action_CreateForecast](#actioncreateforecast) : `Boolean`
- [Action_CreateOrder](#actioncreateorder) : `Boolean`
- [Action_Ignore](#actionignore) : `Boolean`
- [Action_CloseOrder](#actioncloseorder) : `Boolean`
- [Action_UpdateOrder](#actionupdateorder) : `Boolean`
- [WarehouseWithCustomerCode](#warehousewithcustomercode) : `Text`
- [ds](#ds)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Regular Functions (14):**

- [setDefaultActions](#setdefaultactions)
- [newFromText](#newfromtext) (1 param)
- [newFromCustomerOrder](#newfromcustomerorder) (1 param)
- [getWarehouseWithCustomerCode](#getwarehousewithcustomercode) → `Text`
- [setAction](#setaction)
- [_setActions](#_setactions) (1 param)
- [_copyItemNumber](#_copyitemnumber)
- [_setActionIgnore](#_setactionignore) (1 param)
- [process](#process)
- [_setNewCustomer_OrderEntity](#_setnewcustomer_orderentity) → `cs.Customer_OrderEntity`
- [process_CreateForecast](#process_createforecast)
- [process_CreateOrder](#process_createorder)
- [process_UpdateOrder](#process_updateorder)
- [process_CloseOrder](#process_closeorder)

**🔍 Getters (13):**

- [IsActionSet](#isactionset) → `Boolean`
- [IsBacklog](#isbacklog) → `Boolean`
- [IsForecast](#isforecast) → `Boolean`
- [IsItemMissing](#isitemmissing) → `Boolean`
- [IsNewOrder](#isneworder) → `Boolean`
- [IsExistingOrder](#isexistingorder) → `Boolean`
- [IsExistingOrderModified](#isexistingordermodified) → `Boolean`
- [WeekNumberText](#weeknumbertext) → `Text`
- [OrderBatchNumber](#orderbatchnumber) → `Text`
- [OurPartName](#ourpartname) → `Text`
- [Meta->$Meta](#meta->$meta) → `cs.UI.ListBoxMeta`
- [StatusText->$StatusText](#statustext->$statustext) → `Text`
- [ActionText->$ActionText](#actiontext->$actiontext) → `Text`

---

## 📋 Properties

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

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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
Function _setNewCustomer_OrderEntity -> cs.Customer_OrderEntity
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

### 🔍 Getters

#### IsActionSet {#isactionset}
 `[🔍 getter]`

```4d
Function IsActionSet -> Boolean
```

**Returns:** `Boolean`

---

#### IsBacklog {#isbacklog}
 `[🔍 getter]`

```4d
Function IsBacklog -> Boolean
```

**Returns:** `Boolean`

---

#### IsForecast {#isforecast}
 `[🔍 getter]`

```4d
Function IsForecast -> Boolean
```

**Returns:** `Boolean`

---

#### IsItemMissing {#isitemmissing}
 `[🔍 getter]`

```4d
Function IsItemMissing -> Boolean
```

**Returns:** `Boolean`

---

#### IsNewOrder {#isneworder}
 `[🔍 getter]`

```4d
Function IsNewOrder -> Boolean
```

**Returns:** `Boolean`

---

#### IsExistingOrder {#isexistingorder}
 `[🔍 getter]`

```4d
Function IsExistingOrder -> Boolean
```

**Returns:** `Boolean`

---

#### IsExistingOrderModified {#isexistingordermodified}
 `[🔍 getter]`

```4d
Function IsExistingOrderModified -> Boolean
```

**Returns:** `Boolean`

---

#### WeekNumberText {#weeknumbertext}
 `[🔍 getter]`

```4d
Function WeekNumberText -> Text
```

**Returns:** `Text`

---

#### OrderBatchNumber {#orderbatchnumber}
 `[🔍 getter]`

```4d
Function OrderBatchNumber -> Text
```

**Returns:** `Text`

---

#### OurPartName {#ourpartname}
 `[🔍 getter]`

```4d
Function OurPartName -> Text
```

**Returns:** `Text`

---

#### Meta->$Meta {#meta->$meta}
 `[🔍 getter]`

```4d
Function Meta->$Meta -> cs.UI.ListBoxMeta
```

**Returns:** `cs.UI.ListBoxMeta`

---

#### StatusText->$StatusText {#statustext->$statustext}
 `[🔍 getter]`

```4d
Function StatusText->$StatusText -> Text
```

**Returns:** `Text`

---

#### ActionText->$ActionText {#actiontext->$actiontext}
 `[🔍 getter]`

```4d
Function ActionText->$ActionText -> Text
```

**Returns:** `Text`

---

---

*Generated from ProcurementProgramLine.4dm*
