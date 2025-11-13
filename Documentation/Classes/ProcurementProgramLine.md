---
layout : default
title : ProcurementProgramLine
parent : Classes
---
# ProcurementProgramLine

📊 **Overview:** 18 Properties | 1 Constructor | 14 Functions | 13 Getters

## 📝 Description

🗨️ $Column.BackgroundColor:=Color.PastelGreen

🕐 *Last updated: 2025-11-13T00:47:53.452Z*

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

**⚙️ Functions (14):**

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

### Quick Reference

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `ItemNumber` | `Text` | - |  |
| `OrderNumber` | `Text` | - |  |
| `Quantity` | `Integer` | - |  |
| `DueDate` | `Date` | - |  |
| `ItemDescription` | `Text` | - |  |
| `Vmi` | `Boolean` | - |  |
| `Warehouse` | `Text` | - |  |
| `Product_OptionEntity` | `cs.Product_OptionEntity` | - |  |
| `Customer_OrderEntity` | `cs.Customer_OrderEntity` | - |  |
| `ProcurementProgram` | `cs.ProcurementProgram` | - |  |
| `RemovedFromProgram` | `Boolean` | - |  |
| `Action_CreateForecast` | `Boolean` | - |  |
| `Action_CreateOrder` | `Boolean` | - |  |
| `Action_Ignore` | `Boolean` | - |  |
| `Action_CloseOrder` | `Boolean` | - |  |
| `Action_UpdateOrder` | `Boolean` | - |  |
| `WarehouseWithCustomerCode` | `Text` | - |  |
| `ds` | *Not specified* | `DataStore(0)` |  |

### Detailed Information

#### ItemNumber {#itemnumber}

**Type:** `Text`

---

#### OrderNumber {#ordernumber}

**Type:** `Text`

---

#### Quantity {#quantity}

**Type:** `Integer`

---

#### DueDate {#duedate}

**Type:** `Date`

---

#### ItemDescription {#itemdescription}

**Type:** `Text`

---

#### Vmi {#vmi}

**Type:** `Boolean`

---

#### Warehouse {#warehouse}

**Type:** `Text`

---

#### Product_OptionEntity {#productoptionentity}

**Type:** `cs.Product_OptionEntity`

---

#### Customer_OrderEntity {#customerorderentity}

**Type:** `cs.Customer_OrderEntity`

---

#### ProcurementProgram {#procurementprogram}

**Type:** `cs.ProcurementProgram`

---

#### RemovedFromProgram {#removedfromprogram}

**Type:** `Boolean`

---

#### Action_CreateForecast {#actioncreateforecast}

**Type:** `Boolean`

---

#### Action_CreateOrder {#actioncreateorder}

**Type:** `Boolean`

---

#### Action_Ignore {#actionignore}

**Type:** `Boolean`

---

#### Action_CloseOrder {#actioncloseorder}

**Type:** `Boolean`

---

#### Action_UpdateOrder {#actionupdateorder}

**Type:** `Boolean`

---

#### WarehouseWithCustomerCode {#warehousewithcustomercode}

**Type:** `Text`

---

#### ds {#ds}

**Type:** *Not specified*

**Default Value:** `DataStore(0)`

---

## ⚙️ Functions

### 🏗️ Constructors

### ⚙️ Regular Functions

### 🔍 Getters

---

*Generated from ProcurementProgramLine.4dm*
