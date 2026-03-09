---
layout : default
title : Stock
parent : Classes
---
# Stock [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Stock.4dm)

📊 **Overview:** 1 Constructor | 17 Functions

## 📝 Description

Manages finished goods stock movements for a works order, supporting move (transfer between locations) and adjust (increment/decrement) operations with transaction management, entity locking, and detailed movement logging.

🕐 *Last updated: 2026-03-09T14:45:31.666Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [adjust](#adjust) (5 params) → `$lockObject : Object`
    - [move](#move) (5 params) → `$lockObject : Object`
    - [SetNewStockQuarantineStatus](#setnewstockquarantinestatus) (1 param) → `$lockObject : Object`
    - [Quarantine_Stock](#quarantine_stock) (2 params) → `$lockObject : Object`
    - [Quarantine_Release](#quarantine_release) (2 params) → `$lockObject : Object`
    - [Quarantine_Scrap](#quarantine_scrap) (2 params) → `$lockObject : Object`
    - [startTransaction](#starttransaction)
    - [validateTransaction](#validatetransaction)
    - [cancelTransaction](#canceltransaction)
    - [InTransaction](#intransaction) → `$InTransaction : Boolean`
    - [_RecordStockMovement](#_recordstockmovement) (7 params) → `$Stock_MovementEntity : cs.Stock_MovementEntity`
    - [SetQuarantineReason](#setquarantinereason) (1 param) → `$lockObject : Object`
    - [GetAvailableQuantity](#getavailablequantity) (1 param) → `$AvailableQuantity : Integer`
    - [GetQuarantinedQuantity](#getquarantinedquantity) → `$QuarantinedQuantity : Integer`
    - [GetStockEntitySelection](#getstockentityselection) → `$EntitySelection : 4D.EntitySelection`
    - [GetNewStockQuarantineStatus](#getnewstockquarantinestatus) → `$QuarantineNewStock : Boolean`
    - [GetQuarantineReason](#getquarantinereason) → `$QuarantineReason : Text`

---

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($DataStore : 4D.DataStoreImplementation; $WorksOrder : Integer)
```

Initializes stock management for a works order, setting up locations and default stock status

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DataStore` | `4D.DataStoreImplementation` | - | - |
| `$WorksOrder` | `Integer` | - | - |

---

## Functions {#functions}

### Regular Functions

#### adjust {#adjust}


```4d
Function adjust($LocationID : Integer; $AdjustmentQuantity : Integer; $CreateStockMovement : Boolean; $AdjustmentReason : Text; $AdviceNote : Integer) -> $lockObject : Object
```

Adjusts stock quantity at a specific location and optionally records the movement

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LocationID` | `Integer` | - | - |
| `$AdjustmentQuantity` | `Integer` | - | - |
| `$CreateStockMovement` | `Boolean` | - | - |
| `$AdjustmentReason` | `Text` | - | - |
| `$AdviceNote` | `Integer` | - | - |

**Returns:** `Object`

---

#### move {#move}


```4d
Function move($FromLocation : Integer; $ToLocation : Integer; $AdjustmentQuantity : Integer; $AdjustmentReason : Text; $AdviceNote : Integer) -> $lockObject : Object
```

Moves stock from one location to another in a single transaction, recording the movement

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FromLocation` | `Integer` | - | - |
| `$ToLocation` | `Integer` | - | - |
| `$AdjustmentQuantity` | `Integer` | - | - |
| `$AdjustmentReason` | `Text` | - | - |
| `$AdviceNote` | `Integer` | - | - |

**Returns:** `Object`

---

#### SetNewStockQuarantineStatus {#setnewstockquarantinestatus}


```4d
Function SetNewStockQuarantineStatus($QuarantineNewStock : Boolean) -> $lockObject : Object
```

Sets whether new stock for this works order should be quarantined by default

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QuarantineNewStock` | `Boolean` | - | - |

**Returns:** `Object`

---

#### Quarantine_Stock {#quarantine_stock}


```4d
Function Quarantine_Stock($QuantityToQuarantine : Integer; $QuarantineReason : Text) -> $lockObject : Object
```

Moves the specified quantity of finished stock to quarantine status with a reason

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QuantityToQuarantine` | `Integer` | - | - |
| `$QuarantineReason` | `Text` | - | - |

**Returns:** `Object`

---

#### Quarantine_Release {#quarantine_release}


```4d
Function Quarantine_Release($QuantityToRelease : Integer; $ReleaseReason : Text) -> $lockObject : Object
```

Releases quarantined stock back to finished goods with a release reason

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QuantityToRelease` | `Integer` | - | - |
| `$ReleaseReason` | `Text` | - | - |

**Returns:** `Object`

---

#### Quarantine_Scrap {#quarantine_scrap}


```4d
Function Quarantine_Scrap($QuantityToScrap : Integer; $ScrapReason : Text) -> $lockObject : Object
```

Scraps quarantined stock with a scrap reason and records the movement

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QuantityToScrap` | `Integer` | - | - |
| `$ScrapReason` | `Text` | - | - |

**Returns:** `Object`

---

#### startTransaction {#starttransaction}


```4d
Function startTransaction
```

Begins a database transaction and increments the transaction level counter

---

#### validateTransaction {#validatetransaction}


```4d
Function validateTransaction
```

Commits the current transaction and decrements the transaction level counter

---

#### cancelTransaction {#canceltransaction}


```4d
Function cancelTransaction
```

Rolls back the current transaction and decrements the transaction level counter

---

#### InTransaction {#intransaction}


```4d
Function InTransaction -> $InTransaction : Boolean
```

Returns whether a transaction is currently active based on the transaction level counter

**Returns:** `Boolean`

---

#### _RecordStockMovement {#_recordstockmovement}


```4d
Function _RecordStockMovement($Quantity : Integer; $From_LocationID : Integer; $To_LocationID : Integer; $From_Type : Text; $To_Type : Text; $Reason : Text; $AdviceNote : Integer) -> $Stock_MovementEntity : cs.Stock_MovementEntity
```

Records a stock movement entry with source/destination locations, types, and reason

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Quantity` | `Integer` | - | - |
| `$From_LocationID` | `Integer` | - | - |
| `$To_LocationID` | `Integer` | - | - |
| `$From_Type` | `Text` | - | - |
| `$To_Type` | `Text` | - | - |
| `$Reason` | `Text` | - | - |
| `$AdviceNote` | `Integer` | - | - |

**Returns:** `cs.Stock_MovementEntity`

---

#### SetQuarantineReason {#setquarantinereason}


```4d
Function SetQuarantineReason($QuarantineReason : Text) -> $lockObject : Object
```

Sets the reason for quarantining stock on this works order

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QuarantineReason` | `Text` | - | - |

**Returns:** `Object`

---

#### GetAvailableQuantity {#getavailablequantity}


```4d
Function GetAvailableQuantity($StockLocation : Integer) -> $AvailableQuantity : Integer
```

Returns the total available stock quantity at the specified location (or default location if 0)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StockLocation` | `Integer` | - | - |

**Returns:** `Integer`

---

#### GetQuarantinedQuantity {#getquarantinedquantity}


```4d
Function GetQuarantinedQuantity -> $QuarantinedQuantity : Integer
```

Returns the total quantity of stock currently in quarantine for this works order

**Returns:** `Integer`

---

#### GetStockEntitySelection {#getstockentityselection}


```4d
Function GetStockEntitySelection -> $EntitySelection : 4D.EntitySelection
```

Returns an entity selection of all non-zero stock records for this works order

**Returns:** `4D.EntitySelection`

---

#### GetNewStockQuarantineStatus {#getnewstockquarantinestatus}


```4d
Function GetNewStockQuarantineStatus -> $QuarantineNewStock : Boolean
```

Returns whether new stock for this works order is set to be quarantined

**Returns:** `Boolean`

---

#### GetQuarantineReason {#getquarantinereason}


```4d
Function GetQuarantineReason -> $QuarantineReason : Text
```

Returns the reason stored for quarantining stock on this works order

**Returns:** `Text`

---

---

*Generated from Stock.4dm*
