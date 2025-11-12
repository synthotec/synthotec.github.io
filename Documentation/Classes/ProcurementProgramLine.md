# ProcurementProgramLine

## Description

$Column.BackgroundColor:=Color.PastelGreen

## Table of Contents

### Properties

- [ItemNumber](#itemnumber)
- [OrderNumber](#ordernumber)
- [Quantity](#quantity)
- [DueDate](#duedate)
- [ItemDescription](#itemdescription)
- [Vmi](#vmi)
- [Warehouse](#warehouse)
- [Product_OptionEntity](#productoptionentity)
- [Customer_OrderEntity](#customerorderentity)
- [ProcurementProgram](#procurementprogram)
- [RemovedFromProgram](#removedfromprogram)
- [Action_CreateForecast](#actioncreateforecast)
- [Action_CreateOrder](#actioncreateorder)
- [Action_Ignore](#actionignore)
- [Action_CloseOrder](#actioncloseorder)
- [Action_UpdateOrder](#actionupdateorder)
- [WarehouseWithCustomerCode](#warehousewithcustomercode)
- [ds](#ds)

### Functions

- [IsActionSet() [getter]](#isactionset)
- [setDefaultActions()](#setdefaultactions)
- [IsBacklog() [getter]](#isbacklog)
- [IsForecast() [getter]](#isforecast)
- [IsItemMissing() [getter]](#isitemmissing)
- [IsNewOrder() [getter]](#isneworder)
- [IsExistingOrder() [getter]](#isexistingorder)
- [IsExistingOrderModified() [getter]](#isexistingordermodified)
- [WeekNumberText() [getter]](#weeknumbertext)
- [OrderBatchNumber() [getter]](#orderbatchnumber)
- [newFromText()](#newfromtext)
- [newFromCustomerOrder()](#newfromcustomerorder)
- [getWarehouseWithCustomerCode()](#getwarehousewithcustomercode)
- [OurPartName() [getter]](#ourpartname)
- [Meta->$Meta() [getter]](#meta->$meta)
- [StatusText->$StatusText() [getter]](#statustext->$statustext)
- [ActionText->$ActionText() [getter]](#actiontext->$actiontext)
- [setAction()](#setaction)
- [_setActions()](#_setactions)
- [_copyItemNumber()](#_copyitemnumber)
- [_setActionIgnore()](#_setactionignore)
- [process()](#process)
- [_setNewCustomer_OrderEntity()](#_setnewcustomer_orderentity)
- [process_CreateForecast()](#process_createforecast)
- [process_CreateOrder()](#process_createorder)
- [process_UpdateOrder()](#process_updateorder)
- [process_CloseOrder()](#process_closeorder)

---

## Properties

### ItemNumber {#itemnumber}

**Type:** `Text`

---

### OrderNumber {#ordernumber}

**Type:** `Text`

---

### Quantity {#quantity}

**Type:** `Integer`

---

### DueDate {#duedate}

**Type:** `Date`

---

### ItemDescription {#itemdescription}

**Type:** `Text`

---

### Vmi {#vmi}

**Type:** `Boolean`

---

### Warehouse {#warehouse}

**Type:** `Text`

---

### Product_OptionEntity {#productoptionentity}

**Type:** `cs.Product_OptionEntity`

---

### Customer_OrderEntity {#customerorderentity}

**Type:** `cs.Customer_OrderEntity`

---

### ProcurementProgram {#procurementprogram}

**Type:** `cs.ProcurementProgram`

---

### RemovedFromProgram {#removedfromprogram}

**Type:** `Boolean`

---

### Action_CreateForecast {#actioncreateforecast}

**Type:** `Boolean`

---

### Action_CreateOrder {#actioncreateorder}

**Type:** `Boolean`

---

### Action_Ignore {#actionignore}

**Type:** `Boolean`

---

### Action_CloseOrder {#actioncloseorder}

**Type:** `Boolean`

---

### Action_UpdateOrder {#actionupdateorder}

**Type:** `Boolean`

---

### WarehouseWithCustomerCode {#warehousewithcustomercode}

**Type:** `Text`

---

### ds {#ds}

**Type:** *Not specified*

**Default Value:** `DataStore(0)`

---

## Functions

### IsActionSet {#isactionset}
 `[getter]`

```4d
Function IsActionSet -> Boolean
```

**Returns:** `Boolean`

---

### setDefaultActions {#setdefaultactions}


```4d
Function setDefaultActions
```

---

### IsBacklog {#isbacklog}
 `[getter]`

```4d
Function IsBacklog -> Boolean
```

**Returns:** `Boolean`

---

### IsForecast {#isforecast}
 `[getter]`

```4d
Function IsForecast -> Boolean
```

**Returns:** `Boolean`

---

### IsItemMissing {#isitemmissing}
 `[getter]`

```4d
Function IsItemMissing -> Boolean
```

**Returns:** `Boolean`

---

### IsNewOrder {#isneworder}
 `[getter]`

```4d
Function IsNewOrder -> Boolean
```

**Returns:** `Boolean`

---

### IsExistingOrder {#isexistingorder}
 `[getter]`

```4d
Function IsExistingOrder -> Boolean
```

**Returns:** `Boolean`

---

### IsExistingOrderModified {#isexistingordermodified}
 `[getter]`

```4d
Function IsExistingOrderModified -> Boolean
```

**Returns:** `Boolean`

---

### WeekNumberText {#weeknumbertext}
 `[getter]`

```4d
Function WeekNumberText -> Text
```

**Returns:** `Text`

---

### OrderBatchNumber {#orderbatchnumber}
 `[getter]`

```4d
Function OrderBatchNumber -> Text
```

**Returns:** `Text`

---

### newFromText {#newfromtext}


```4d
Function newFromText($Line : Text)
```

---

### newFromCustomerOrder {#newfromcustomerorder}


```4d
Function newFromCustomerOrder($Customer_OrderEntity : cs.Customer_OrderEntity)
```

---

### getWarehouseWithCustomerCode {#getwarehousewithcustomercode}


```4d
Function getWarehouseWithCustomerCode -> Text
```

**Returns:** `Text`

---

### OurPartName {#ourpartname}
 `[getter]`

```4d
Function OurPartName -> Text
```

**Returns:** `Text`

---

### Meta->$Meta {#meta->$meta}
 `[getter]`

```4d
Function Meta->$Meta -> cs.UI.ListBoxMeta
```

**Returns:** `cs.UI.ListBoxMeta`

---

### StatusText->$StatusText {#statustext->$statustext}
 `[getter]`

```4d
Function StatusText->$StatusText -> Text
```

**Returns:** `Text`

---

### ActionText->$ActionText {#actiontext->$actiontext}
 `[getter]`

```4d
Function ActionText->$ActionText -> Text
```

**Returns:** `Text`

---

### setAction {#setaction}


```4d
Function setAction
```

---

### _setActions {#_setactions}


```4d
Function _setActions($ActiveActionProperty : Text)
```

---

### _copyItemNumber {#_copyitemnumber}


```4d
Function _copyItemNumber
```

---

### _setActionIgnore {#_setactionignore}


```4d
Function _setActionIgnore($IgnoreForAllOrders : Boolean)
```

---

### process {#process}


```4d
Function process
```

---

### _setNewCustomer_OrderEntity {#_setnewcustomer_orderentity}


```4d
Function _setNewCustomer_OrderEntity -> cs.Customer_OrderEntity
```

**Returns:** `cs.Customer_OrderEntity`

---

### process_CreateForecast {#process_createforecast}


```4d
Function process_CreateForecast
```

---

### process_CreateOrder {#process_createorder}


```4d
Function process_CreateOrder
```

---

### process_UpdateOrder {#process_updateorder}


```4d
Function process_UpdateOrder
```

---

### process_CloseOrder {#process_closeorder}


```4d
Function process_CloseOrder
```

---

---

*Generated from ProcurementProgramLine.4dm*
*Last updated: 2025-11-12T17:04:22.207Z*
