---
layout : default
title : ProcurementProgramLine
parent : Classes
---
# ProcurementProgramLine [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProcurementProgramLine.4dm)

📊 **Overview:** 18 Properties | 1 Constructor | 14 Functions | 13 Getters

## 📝 Description

Sets default action flags based on line type (forecast, backlog, new order, existing order, etc.)

🕐 *Last updated: 2025-12-10T11:45:23.864Z*

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
| `ItemNumber` | `Text` | - | Customer's item reference number |
| `OrderNumber` | `Text` | - | Order number or status (FORECAST, BACKLOG, BACKORDER, or actual order number) |
| `Quantity` | `Integer` | - | Quantity ordered or forecasted |
| `DueDate` | `Date` | - | Customer delivery date |
| `ItemDescription` | `Text` | - | Description of the item from procurement program |
| `Vmi` | `Boolean` | - | True if this is a Vendor Managed Inventory item |
| `Warehouse` | `Text` | - | Warehouse location code (e.g., NTN, SNR) |
| `Product_OptionEntity` | `cs.Product_OptionEntity` | - | Linked product option (matched by CustomerReference), can be Null if not found |
| `Customer_OrderEntity` | `cs.Customer_OrderEntity` | - | Existing customer order entity if line matches an existing order, otherwise Null |
| `ProcurementProgram` | `cs.ProcurementProgram` | - | Parent procurement program object |
| `RemovedFromProgram` | `Boolean` | - | True if this order exists in system but was not in latest procurement program file |
| `Action_CreateForecast` | `Boolean` | - | True if action is to create a forecast order |
| `Action_CreateOrder` | `Boolean` | - | True if action is to create a new customer order |
| `Action_Ignore` | `Boolean` | - | True if no action should be taken (e.g., backlog items) |
| `Action_CloseOrder` | `Boolean` | - | True if existing order should be closed |
| `Action_UpdateOrder` | `Boolean` | - | True if existing order quantity should be updated |
| `WarehouseWithCustomerCode` | `Text` | - | Warehouse code with customer code appended in format "NTN (123)" |
| `ds` | *Not specified* | `DataStore(0)` | Reference to main datastore |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($TextLineOrCustomer_OrderEntity : Variant; $ProcurementProgram : cs.ProcurementProgram)
```

Creates a procurement program line from either tab-delimited text or an existing Customer_OrderEntity

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

Sets default action flags based on line type (forecast, backlog, new order, existing order, etc.)

---

#### newFromText {#newfromtext}


```4d
Function newFromText($Line : Text)
```

Parses tab-delimited text line and populates properties, attempts to match product and existing order

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Line` | `Text` | - | - |

---

#### newFromCustomerOrder {#newfromcustomerorder}


```4d
Function newFromCustomerOrder($Customer_OrderEntity : cs.Customer_OrderEntity)
```

Populates properties from an existing Customer_OrderEntity (used for orders removed from program)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Customer_OrderEntity` | `cs.Customer_OrderEntity` | - | - |

---

#### getWarehouseWithCustomerCode {#getwarehousewithcustomercode}


```4d
Function getWarehouseWithCustomerCode -> Text
```

Returns warehouse code with customer code appended in format "NTN (123)", or just warehouse code if customer not found

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

Returns true if any action flag is set for this line

**Returns:** `Boolean`

---

#### IsBacklog {#isbacklog}
 `[🔍 get only]`

```4d
Function get IsBacklog -> Boolean
```

Returns true if order status is BACKLOG or BACKORDER

**Returns:** `Boolean`

---

#### IsExistingOrder {#isexistingorder}
 `[🔍 get only]`

```4d
Function get IsExistingOrder -> Boolean
```

Returns true if both product and matching customer order exist

**Returns:** `Boolean`

---

#### IsExistingOrderModified {#isexistingordermodified}
 `[🔍 get only]`

```4d
Function get IsExistingOrderModified -> Boolean
```

Returns true if existing order quantity differs from procurement program quantity

**Returns:** `Boolean`

---

#### IsForecast {#isforecast}
 `[🔍 get only]`

```4d
Function get IsForecast -> Boolean
```

Returns true if order status is FORECAST

**Returns:** `Boolean`

---

#### IsItemMissing {#isitemmissing}
 `[🔍 get only]`

```4d
Function get IsItemMissing -> Boolean
```

Returns true if item number could not be matched to a Product_Option in the system

**Returns:** `Boolean`

---

#### IsNewOrder {#isneworder}
 `[🔍 get only]`

```4d
Function get IsNewOrder -> Boolean
```

Returns true if product exists but no matching customer order found

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

Returns batch number in format "YYYY-MM-DD" for grouping orders

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

Returns week number in format "YYYY-WW"

**Returns:** `Text`

---

---

*Generated from ProcurementProgramLine.4dm*
