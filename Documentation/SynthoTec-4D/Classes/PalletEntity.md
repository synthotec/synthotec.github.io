---
layout : default
title : PalletEntity
parent : Classes
---
# PalletEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PalletEntity.4dm)

📊 **Overview:** 9 Functions | 5 Getters

## 📝 Description

Entity representing a physical pallet loaded with packed boxes. Provides net and gross weight calculation from associated box labels, print job creation for pallet labels, and despatch/verification operations.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.330Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [createPrintJob](#createprintjob) (2 params) → `$Success : Boolean`
    - [getWorksOrderCollection](#getworksordercollection) → `Collection`
    - [getTotalQuantity](#gettotalquantity) (1 param) → `Integer`
    - [getTotalBoxes](#gettotalboxes) (1 param) → `Integer`
    - [generateQR](#generateqr) → `Picture` 🖥️
    - [getStockListBoxObject](#getstocklistboxobject) → `Object` 🖥️
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
    - [transfer](#transfer) (1 param) → `Boolean` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [FirstBoxLabelsEntity](#firstboxlabelsentity) 🔍 → `cs.BoxLabelsEntity`
    - [GrossWeightKg](#grossweightkg) 🔍 → `Real`
    - [HasMigrationID](#hasmigrationid) 🔍 → `Boolean`
    - [NetWeightKg](#netweightkg) 🔍 → `Real`
    - [QRObject](#qrobject) 🔍 → `Object`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### createPrintJob {#createprintjob}


```4d
Function createPrintJob($StaffID : Integer; $PrinterID : Integer) -> $Success : Boolean
```

Creates a print job for this pallet label and marks pallet as printed

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StaffID` | `Integer` | - | - |
| `$PrinterID` | `Integer` | - | - |

**Returns:** `Boolean`

---

#### getWorksOrderCollection {#getworksordercollection}


```4d
Function getWorksOrderCollection -> Collection
```

Returns a collection of distinct works order IDs from all boxes on this pallet

**Returns:** `Collection`

---

#### getTotalQuantity {#gettotalquantity}


```4d
Function getTotalQuantity($WorksOrderEntity : Integer) -> Integer
```

Returns the total quantity of items on this pallet, optionally filtered by works order

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$WorksOrderEntity` | `Integer` | - | - |

**Returns:** `Integer`

---

#### getTotalBoxes {#gettotalboxes}


```4d
Function getTotalBoxes($WorksOrderEntity : Integer) -> Integer
```

Returns the total number of boxes on this pallet, optionally filtered by works order

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$WorksOrderEntity` | `Integer` | - | - |

**Returns:** `Integer`

---

#### generateQR {#generateqr}
 `[🖥️ local]`

```4d
Function generateQR -> Picture
```

Generates a QR code picture from the pallet QR object

**Returns:** `Picture`

---

#### getStockListBoxObject {#getstocklistboxobject}
 `[🖥️ local]`

```4d
Function getStockListBoxObject -> Object
```

Returns an object representing this pallet for display in stock list boxes

**Returns:** `Object`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.PalletEntity) -> $Collection : Collection
```

Returns migration rules for syncing pallet data during migration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.PalletEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.PalletEntity)
```

Syncs related box label and print job selections during migration (currently commented out)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.PalletEntity` | - | - |

---

#### transfer {#transfer}
 `[🖥️ local]`

```4d
Function transfer($ToLocation : Integer) -> Boolean
```

Transfers this pallet to a new location by moving stock and updating location, within a transaction

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToLocation` | `Integer` | - | - |

**Returns:** `Boolean`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### FirstBoxLabelsEntity {#firstboxlabelsentity}
 `[🔍 get only]`

```4d
Function get FirstBoxLabelsEntity -> cs.BoxLabelsEntity
```

Returns the first box label on this pallet ordered by works order then ID

**Returns:** `cs.BoxLabelsEntity`

---

#### GrossWeightKg {#grossweightkg}
 `[🔍 get only, 🖥️ local]`

```4d
Function get GrossWeightKg -> Real
```

Returns the total gross weight in kg of all boxes plus 20kg for pallet weight

**Returns:** `Real`

---

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

Returns true if this pallet has a valid migration ID

**Returns:** `Boolean`

---

#### NetWeightKg {#netweightkg}
 `[🔍 get only, 🖥️ local]`

```4d
Function get NetWeightKg -> Real
```

Returns the total net weight in kg of all boxes on this pallet

**Returns:** `Real`

---

#### QRObject {#qrobject}
 `[🔍 get only]`

```4d
Function get QRObject -> Object
```

Returns an object containing pallet data for QR code generation

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Pallet](../Tables/Pallet.md) - ORDA Entity class for Pallet table

### � Related Classes

- [Pallet](Pallet.md) - ORDA DataClass class for Pallet table
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

*Generated from PalletEntity.4dm*
