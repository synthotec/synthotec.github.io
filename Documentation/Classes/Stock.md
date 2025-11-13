---
layout : default
title : Stock
parent : Classes
---
# Stock

📊 **Overview:** 1 Constructor | 17 Functions

🕐 *Last updated: 2025-11-13T13:29:03.549Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Functions (17):**

- [adjust](#adjust) (5 params) → `Object`
- [move](#move) (5 params) → `Object`
- [SetNewStockQuarantineStatus](#setnewstockquarantinestatus) (1 param) → `Object`
- [Quarantine_Stock](#quarantine_stock) (2 params) → `Object`
- [Quarantine_Release](#quarantine_release) (2 params) → `Object`
- [Quarantine_Scrap](#quarantine_scrap) (2 params) → `Object`
- [startTransaction](#starttransaction)
- [validateTransaction](#validatetransaction)
- [cancelTransaction](#canceltransaction)
- [InTransaction](#intransaction) → `Boolean`
- [_RecordStockMovement](#_recordstockmovement) (7 params) → `cs.Stock_MovementEntity`
- [SetQuarantineReason](#setquarantinereason) (1 param) → `Object`
- [GetAvailableQuantity](#getavailablequantity) (1 param) → `Integer`
- [GetQuarantinedQuantity](#getquarantinedquantity) → `Integer`
- [GetStockEntitySelection](#getstockentityselection) → `4D.EntitySelection`
- [GetNewStockQuarantineStatus](#getnewstockquarantinestatus) → `Boolean`
- [GetQuarantineReason](#getquarantinereason) → `Text`

### 🔗 Related Items

- [Classes](#-related-classes) (1)

---

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

#### adjust {#adjust}


```4d
Function adjust($LocationID : Integer; $AdjustmentQuantity : Integer; $CreateStockMovement : Boolean; $AdjustmentReason : Text; $AdviceNote : Integer) -> Object
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
Function move($FromLocation : Integer; $ToLocation : Integer; $AdjustmentQuantity : Integer; $AdjustmentReason : Text; $AdviceNote : Integer) -> Object
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
Function SetNewStockQuarantineStatus($QuarantineNewStock : Boolean) -> Object
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QuarantineNewStock` | `Boolean` | - | - |

**Returns:** `Object`

---

#### Quarantine_Stock {#quarantine_stock}


```4d
Function Quarantine_Stock($QuantityToQuarantine : Integer; $QuarantineReason : Text) -> Object
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
Function Quarantine_Release($QuantityToRelease : Integer; $ReleaseReason : Text) -> Object
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
Function Quarantine_Scrap($QuantityToScrap : Integer; $ScrapReason : Text) -> Object
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
Function InTransaction -> Boolean
```

**Returns:** `Boolean`

---

#### _RecordStockMovement {#_recordstockmovement}


```4d
Function _RecordStockMovement($Quantity : Integer; $From_LocationID : Integer; $To_LocationID : Integer; $From_Type : Text; $To_Type : Text; $Reason : Text; $AdviceNote : Integer) -> cs.Stock_MovementEntity
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
Function SetQuarantineReason($QuarantineReason : Text) -> Object
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QuarantineReason` | `Text` | - | - |

**Returns:** `Object`

---

#### GetAvailableQuantity {#getavailablequantity}


```4d
Function GetAvailableQuantity($StockLocation : Integer) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StockLocation` | `Integer` | - | - |

**Returns:** `Integer`

---

#### GetQuarantinedQuantity {#getquarantinedquantity}


```4d
Function GetQuarantinedQuantity -> Integer
```

**Returns:** `Integer`

---

#### GetStockEntitySelection {#getstockentityselection}


```4d
Function GetStockEntitySelection -> 4D.EntitySelection
```

**Returns:** `4D.EntitySelection`

---

#### GetNewStockQuarantineStatus {#getnewstockquarantinestatus}


```4d
Function GetNewStockQuarantineStatus -> Boolean
```

**Returns:** `Boolean`

---

#### GetQuarantineReason {#getquarantinereason}


```4d
Function GetQuarantineReason -> Text
```

**Returns:** `Text`

---

## 🔗 Related Items

### 📦 Related Classes

- [](.md) - Extends this class

---

*Generated from Stock.4dm*
