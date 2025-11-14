---
layout : default
title : Stock
parent : Classes
---
# Stock [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Stock.4dm)

📊 **Overview:** 1 Constructor | 17 Functions

🕐 *Last updated: 2025-11-14T16:35:59.446Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
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

---

#### validateTransaction {#validatetransaction}


```4d
Function validateTransaction
```

---

#### cancelTransaction {#canceltransaction}


```4d
Function cancelTransaction
```

---

#### InTransaction {#intransaction}


```4d
Function InTransaction -> $InTransaction : Boolean
```

**Returns:** `Boolean`

---

#### _RecordStockMovement {#_recordstockmovement}


```4d
Function _RecordStockMovement($Quantity : Integer; $From_LocationID : Integer; $To_LocationID : Integer; $From_Type : Text; $To_Type : Text; $Reason : Text; $AdviceNote : Integer) -> $Stock_MovementEntity : cs.Stock_MovementEntity
```

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

**Returns:** `Integer`

---

#### GetStockEntitySelection {#getstockentityselection}


```4d
Function GetStockEntitySelection -> $EntitySelection : 4D.EntitySelection
```

**Returns:** `4D.EntitySelection`

---

#### GetNewStockQuarantineStatus {#getnewstockquarantinestatus}


```4d
Function GetNewStockQuarantineStatus -> $QuarantineNewStock : Boolean
```

**Returns:** `Boolean`

---

#### GetQuarantineReason {#getquarantinereason}


```4d
Function GetQuarantineReason -> $QuarantineReason : Text
```

**Returns:** `Text`

---

---

*Generated from Stock.4dm*
