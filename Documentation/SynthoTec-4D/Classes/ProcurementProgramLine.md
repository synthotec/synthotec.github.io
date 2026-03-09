---
layout : default
title : ProcurementProgramLine
parent : Classes
---
# ProcurementProgramLine [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProcurementProgramLine.4dm)

📊 **Overview:** 18 Properties | 1 Constructor | 12 Functions | 14 Getters

## 📝 Description

Represents a single line in a parsed customer procurement schedule (e.g., NTN-SNR), created from tab-delimited text or an existing Customer_OrderEntity. Holds order quantities, due dates, VMI flags, and matched product option and order links, with status flags for ignored or removed lines.

🕐 *Last updated: 2026-03-09T14:45:30.723Z*

---

## 📑 Table of Contents

- [📋 Properties (18)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setDefaultActions](#setdefaultactions)
    - [newFromText](#newfromtext) (1 param)
    - [newFromCustomerOrder](#newfromcustomerorder) (1 param)
    - [findMatchingOrder](#findmatchingorder) → `$Customer_OrderEntity : cs.Customer_OrderEntity`
    - [getWarehouseWithCustomerCode](#getwarehousewithcustomercode) → `Text`
    - [setAction](#setaction)
    - [_toggleIgnore](#_toggleignore)
    - [_copyItemNumber](#_copyitemnumber)
    - [_setOrderFields](#_setorderfields) (2 params)
    - [_setNewCustomer_OrderEntity](#_setnewcustomer_orderentity) → `$Customer_OrderEntity : cs.Customer_OrderEntity`
    - [process_UpdateOrCreateOrder](#process_updateorcreateorder)
    - [process](#process)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [ActionPreview](#actionpreview) 🔍 → `Text`
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
    - [WillCreate](#willcreate) 🔍 → `Boolean`
    - [WillUpdate](#willupdate) 🔍 → `Boolean`

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
| `LastDeliveryQty` | `Integer` | - | Quantity from last delivery booked in by customer |
| `OrderPostNb` | `Text` | - | Order/Post number from last delivery (e.g., "5500417085/00010") |
| `PackingListNb` | `Integer` | - | Packing list (advice note) number from last delivery |
| `Product_OptionEntity` | `cs.Product_OptionEntity` | - | Linked product option (matched by CustomerReference), can be Null if not found |
| `Customer_OrderEntity` | `cs.Customer_OrderEntity` | - | Existing customer order entity if line matches an existing order, otherwise Null |
| `ProcurementProgram` | `cs.ProcurementProgram` | - | Parent procurement program object |
| `RemovedFromProgram` | `Boolean` | - | True if this order exists in system but was not in latest procurement program file |
| `Action_Ignore` | `Boolean` | - | True if this line should be ignored (not processed) |
| `WarehouseWithCustomerCode` | `Text` | - | Warehouse code with customer code appended in format "NTN (123)" |
| `ds` | `4D.DataStoreImplementation` | - | Reference to main datastore |
| `MultipleProduct_OptionRecords` | `Boolean` | `False` | True if the item number matched more than one product option record (ambiguous match) |

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

Sets default ignore flag based on line type (only backlog items and existing orders are ignored by default)

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

#### findMatchingOrder {#findmatchingorder}


```4d
Function findMatchingOrder -> $Customer_OrderEntity : cs.Customer_OrderEntity
```

Attempts to find an existing order that matches this procurement program line

**Returns:** `cs.Customer_OrderEntity`

---

#### getWarehouseWithCustomerCode {#getwarehousewithcustomercode}


```4d
Function getWarehouseWithCustomerCode -> Text
```

Returns warehouse code with customer code; "NTN (*)" if multiple customers match warehouse

**Returns:** `Text`

---

#### setAction {#setaction}


```4d
Function setAction
```

Displays menu for user to toggle ignore action or copy item number for missing items

---

#### _toggleIgnore {#_toggleignore}


```4d
Function _toggleIgnore
```

Toggle ignore action; if confirming ignore, optionally apply to all orders with same item code

---

#### _copyItemNumber {#_copyitemnumber}


```4d
Function _copyItemNumber
```

Copies item number to clipboard and displays confirmation dialog with option to open Product Price Options screen

---

#### _setOrderFields {#_setorderfields}


```4d
Function _setOrderFields($Order : cs.Customer_OrderEntity; $IsCreating : Boolean)
```

Sets fields on Customer_OrderEntity for both create and update paths

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Order` | `cs.Customer_OrderEntity` | - | - |
| `$IsCreating` | `Boolean` | - | - |

---

#### _setNewCustomer_OrderEntity {#_setnewcustomer_orderentity}


```4d
Function _setNewCustomer_OrderEntity -> $Customer_OrderEntity : cs.Customer_OrderEntity
```

Creates a new Customer_OrderEntity, populates all creation fields via _setOrderFields, stores it on This.Customer_OrderEntity, and returns it

**Returns:** `cs.Customer_OrderEntity`

---

#### process_UpdateOrCreateOrder {#process_updateorcreateorder}


```4d
Function process_UpdateOrCreateOrder
```

Find matching order (exact match or forecast fallback for forecasts)

---

#### process {#process}


```4d
Function process
```

Process this line - ignore backlogs and missing items, otherwise update or create

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### ActionPreview {#actionpreview}
 `[🔍 get only]`

```4d
Function get ActionPreview -> Text
```

Returns human-readable description of what will happen when processed

**Returns:** `Text`

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

Returns listbox display metadata with colored backgrounds for status, action, and order details

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

Returns our part name from product if product found; otherwise returns item description from program

**Returns:** `Text`

---

#### StatusText->$StatusText {#statustext->$statustext}
 `[🔍 get only]`

```4d
Function get StatusText->$StatusText -> Text
```

Returns status display text for line (Forecast, Backlog, New Order, Existing Order, Item Missing, or Removed from Program)

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

#### WillCreate {#willcreate}
 `[🔍 get only]`

```4d
Function get WillCreate -> Boolean
```

Returns true if this line will create a new order or forecast

**Returns:** `Boolean`

---

#### WillUpdate {#willupdate}
 `[🔍 get only]`

```4d
Function get WillUpdate -> Boolean
```

Returns true if this line will update an existing order

**Returns:** `Boolean`

---

---

*Generated from ProcurementProgramLine.4dm*
