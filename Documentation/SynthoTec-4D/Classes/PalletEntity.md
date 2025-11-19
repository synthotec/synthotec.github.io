---
layout : default
title : PalletEntity
parent : Classes
---
# PalletEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PalletEntity.4dm)

📊 **Overview:** 9 Functions | 4 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T18:12:03.236Z*

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

**Returns:** `Collection`

---

#### getTotalQuantity {#gettotalquantity}


```4d
Function getTotalQuantity($WorksOrderEntity : Integer) -> Integer
```

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

**Returns:** `Picture`

---

#### getStockListBoxObject {#getstocklistboxobject}
 `[🖥️ local]`

```4d
Function getStockListBoxObject -> Object
```

**Returns:** `Object`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.PalletEntity) -> $Collection : Collection
```

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

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToLocation` | `Integer` | - | - |

**Returns:** `Boolean`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### GrossWeightKg {#grossweightkg}
 `[🔍 get only, 🖥️ local]`

```4d
Function get GrossWeightKg -> Real
```

**Returns:** `Real`

---

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

#### NetWeightKg {#netweightkg}
 `[🔍 get only, 🖥️ local]`

```4d
Function get NetWeightKg -> Real
```

**Returns:** `Real`

---

#### QRObject {#qrobject}
 `[🔍 get only]`

```4d
Function get QRObject -> Object
```

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
