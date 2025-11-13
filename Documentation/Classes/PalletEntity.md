---
layout : default
title : PalletEntity
parent : Classes
---
# PalletEntity

📊 **Overview:** 9 Functions | 4 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T13:52:49.656Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (9):**

- [createPrintJob](#createprintjob) (2 params) → `$Success : Boolean`
- [getWorksOrderCollection](#getworksordercollection) → `Collection`
- [getTotalQuantity](#gettotalquantity) (1 param) → `Integer`
- [getTotalBoxes](#gettotalboxes) (1 param) → `Integer`
- [generateQR](#generateqr) → `Picture` 🖥️
- [getStockListBoxObject](#getstocklistboxobject) → `Object` 🖥️
- [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
- [transfer](#transfer) (1 param) → `Boolean` 🖥️

**🔍 Getters (4):**

- [NetWeightKg](#netweightkg) → `Real`
- [GrossWeightKg](#grossweightkg) → `Real`
- [QRObject](#qrobject) → `Object`
- [HasMigrationID](#hasmigrationid) → `Boolean`

### 🔗 Related Items

- [Tables](#-tables) (1)

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

### 🔍 Getters

#### NetWeightKg {#netweightkg}
 `[🖥️ local, 🔍 getter]`

```4d
Function NetWeightKg -> Real
```

**Returns:** `Real`

---

#### GrossWeightKg {#grossweightkg}
 `[🖥️ local, 🔍 getter]`

```4d
Function GrossWeightKg -> Real
```

**Returns:** `Real`

---

#### QRObject {#qrobject}
 `[🔍 getter]`

```4d
Function QRObject -> Object
```

**Returns:** `Object`

---

#### HasMigrationID {#hasmigrationid}
 `[🖥️ local, 🔍 getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

## 🔗 Related Items

### 🗂️ Tables

- [Pallet](../Tables/Pallet.md) - Entity class

---

*Generated from PalletEntity.4dm*
