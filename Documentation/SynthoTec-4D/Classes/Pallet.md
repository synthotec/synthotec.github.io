---
layout : default
title : Pallet
parent : Classes
---
# Pallet [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Pallet.4dm)

📊 **Overview:** 15 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:12.342Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
    - [getAvailableToPick](#getavailabletopick) (1 param) → `cs.PalletSelection` 🖥️
    - [getUsingScanner](#getusingscanner) (2 params) → `cs.PalletEntity`
    - [Create](#create) (2 params) → `$ResultObject : Object`
    - [Verify](#verify) (3 params) → `$ResultObject : Object`
    - [Print](#print) (2 params) → `$ResultObject : Object`
    - [Delete](#delete) (1 param) → `$ResultObject : Object`
    - [restLoadPalletList](#restloadpalletlist) (1 param) → `Object`
    - [restAddToPallet](#restaddtopallet) (1 param) → `Object`
    - [restCompletePallet](#restcompletepallet) (1 param) → `Object`
    - [restVerifyPallet](#restverifypallet) (1 param) → `Object`
    - [restLocatePallet](#restlocatepallet) (1 param) → `Object`
    - [restDeletePallet](#restdeletepallet) (1 param) → `Object`
    - [restReassignLocation](#restreassignlocation) (1 param) → `Object`
    - [restLoadPallet](#restloadpallet) (1 param) → `Object`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns migration settings for Pallet dataclass: disables linking and preserves ID during entity sync

**Returns:** `Object`

---

#### getAvailableToPick {#getavailabletopick}
 `[🖥️ local]`

```4d
Function getAvailableToPick($ProductEntity : cs.ProductEntity) -> cs.PalletSelection
```

Returns pallets of specified product available for picking: verified, in despatch location, not yet assigned to pick request

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductEntity` | `cs.ProductEntity` | - | - |

**Returns:** `cs.PalletSelection`

---

#### getUsingScanner {#getusingscanner}


```4d
Function getUsingScanner($ScannerObject : Object; $ScannerText : Text) -> cs.PalletEntity
```

Retrieves pallet entity from scanner input: either ScannerObject with PalletID or parsed barcode text (extracts ID from characters 10+)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ScannerObject` | `Object` | - | - |
| `$ScannerText` | `Text` | - | - |

**Returns:** `cs.PalletEntity`

---

#### Create {#create}


```4d
Function Create($BoxLabelIDCollection : Collection; $StaffID : Integer) -> $ResultObject : Object
```

REST endpoint to create new pallet from collection of box label IDs; validates box compatibility, locks entities, and returns result object with success/error info

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BoxLabelIDCollection` | `Collection` | - | - |
| `$StaffID` | `Integer` | - | - |

**Returns:** `Object`

---

#### Verify {#verify}


```4d
Function Verify($PalletID : Integer; $BoxLabelID : Integer; $StaffID : Integer) -> $ResultObject : Object
```

REST endpoint to verify (QA check) pallet contents; locks pallet and boxes, validates integrity, and marks as verified

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PalletID` | `Integer` | - | - |
| `$BoxLabelID` | `Integer` | - | - |
| `$StaffID` | `Integer` | - | - |

**Returns:** `Object`

---

#### Print {#print}


```4d
Function Print($PalletID : Integer; $Printer : Text) -> $ResultObject : Object
```

REST endpoint to print pallet label; creates print job for warehouse label printer

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PalletID` | `Integer` | - | - |
| `$Printer` | `Text` | - | - |

**Returns:** `Object`

---

#### Delete {#delete}


```4d
Function Delete($PalletID : Integer) -> $ResultObject : Object
```

REST endpoint to delete pallet; removes pallet and unlinks associated boxes

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PalletID` | `Integer` | - | - |

**Returns:** `Object`

---

#### restLoadPalletList {#restloadpalletlist}


```4d
Function restLoadPalletList($RestPostDataObject : Object) -> Object
```

REST endpoint for mobile warehouse app; returns scrollable view of all pallets with details, status, and action buttons

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restAddToPallet {#restaddtopallet}


```4d
Function restAddToPallet($RestPostDataObject : Object) -> Object
```

REST endpoint for mobile pallet creation; displays UI to select and add boxes to new pallet with product matching validation

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restCompletePallet {#restcompletepallet}


```4d
Function restCompletePallet($RestPostDataObject : Object) -> Object
```

REST endpoint to finalize pallet; marks pallet as complete and ready for verification/despatch

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restVerifyPallet {#restverifypallet}


```4d
Function restVerifyPallet($RestPostDataObject : Object) -> Object
```

REST endpoint for QA verification; displays pallet contents and allows staff to verify/confirm boxes match pallet manifest

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restLocatePallet {#restlocatepallet}


```4d
Function restLocatePallet($RestPostDataObject : Object) -> Object
```

REST endpoint for locating pallet in warehouse; scans pallet barcode and displays location/contents information

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restDeletePallet {#restdeletepallet}


```4d
Function restDeletePallet($RestPostDataObject : Object) -> Object
```

REST endpoint to delete pallet from warehouse system; removes pallet record and unlinks all boxes

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restReassignLocation {#restreassignlocation}


```4d
Function restReassignLocation($RestPostDataObject : Object) -> Object
```

REST endpoint to change pallet location; allows reassigning pallets to different warehouse locations

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restLoadPallet {#restloadpallet}


```4d
Function restLoadPallet($RestPostDataObject : Object) -> Object
```

REST endpoint for mobile pallet details view; displays pallet contents, boxes, status, and available actions (verify, print, delete, relocate)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Pallet](../Tables/Pallet.md) - ORDA DataClass class for Pallet table

### � Related Classes

- [PalletEntity](PalletEntity.md) - ORDA Entity class for Pallet table
- [PalletSelection](PalletSelection.md) - ORDA EntitySelection class for Pallet table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [%2Atest](../Forms/%2Atest.md) - Data source for %2Atest form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [LocationManager](../Forms/LocationManager.md) - Data source for LocationManager form
- [NSKPalletIDs](../Forms/NSKPalletIDs.md) - Data source for NSKPalletIDs form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form
- [PalletTransfer](../Forms/PalletTransfer.md) - Data source for PalletTransfer form
- [Warehouse](../Forms/Warehouse.md) - Data source for Warehouse form

---

*Generated from Pallet.4dm*
