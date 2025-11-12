# Stock

## Table of Contents

### Functions

- [adjust()](#adjust)
- [move()](#move)
- [SetNewStockQuarantineStatus()](#setnewstockquarantinestatus)
- [Quarantine_Stock()](#quarantine_stock)
- [Quarantine_Release()](#quarantine_release)
- [Quarantine_Scrap()](#quarantine_scrap)
- [startTransaction()](#starttransaction)
- [validateTransaction()](#validatetransaction)
- [cancelTransaction()](#canceltransaction)
- [InTransaction()](#intransaction)
- [_RecordStockMovement()](#_recordstockmovement)
- [SetQuarantineReason()](#setquarantinereason)
- [GetAvailableQuantity()](#getavailablequantity)
- [GetQuarantinedQuantity()](#getquarantinedquantity)
- [GetStockEntitySelection()](#getstockentityselection)
- [GetNewStockQuarantineStatus()](#getnewstockquarantinestatus)
- [GetQuarantineReason()](#getquarantinereason)

---

## Functions

### adjust {#adjust}


```4d
Function adjust($LocationID : Integer; $AdjustmentQuantity : Integer; $CreateStockMovement : Boolean; $AdjustmentReason : Text; $AdviceNote : Integer) -> Object
```

**Returns:** `Object`

---

### move {#move}


```4d
Function move($FromLocation : Integer; $ToLocation : Integer; $AdjustmentQuantity : Integer; $AdjustmentReason : Text; $AdviceNote : Integer) -> Object
```

**Returns:** `Object`

---

### SetNewStockQuarantineStatus {#setnewstockquarantinestatus}


```4d
Function SetNewStockQuarantineStatus($QuarantineNewStock : Boolean) -> Object
```

**Returns:** `Object`

---

### Quarantine_Stock {#quarantine_stock}


```4d
Function Quarantine_Stock($QuantityToQuarantine : Integer; $QuarantineReason : Text) -> Object
```

**Returns:** `Object`

---

### Quarantine_Release {#quarantine_release}


```4d
Function Quarantine_Release($QuantityToRelease : Integer; $ReleaseReason : Text) -> Object
```

**Returns:** `Object`

---

### Quarantine_Scrap {#quarantine_scrap}


```4d
Function Quarantine_Scrap($QuantityToScrap : Integer; $ScrapReason : Text) -> Object
```

**Returns:** `Object`

---

### startTransaction {#starttransaction}


```4d
Function startTransaction
```

---

### validateTransaction {#validatetransaction}


```4d
Function validateTransaction
```

---

### cancelTransaction {#canceltransaction}


```4d
Function cancelTransaction
```

---

### InTransaction {#intransaction}


```4d
Function InTransaction -> Boolean
```

**Returns:** `Boolean`

---

### _RecordStockMovement {#_recordstockmovement}


```4d
Function _RecordStockMovement($Quantity : Integer; $From_LocationID : Integer; $To_LocationID : Integer; $From_Type : Text; $To_Type : Text; $Reason : Text; $AdviceNote : Integer) -> cs.Stock_MovementEntity
```

**Returns:** `cs.Stock_MovementEntity`

---

### SetQuarantineReason {#setquarantinereason}


```4d
Function SetQuarantineReason($QuarantineReason : Text) -> Object
```

**Returns:** `Object`

---

### GetAvailableQuantity {#getavailablequantity}


```4d
Function GetAvailableQuantity($StockLocation : Integer) -> Integer
```

**Returns:** `Integer`

---

### GetQuarantinedQuantity {#getquarantinedquantity}


```4d
Function GetQuarantinedQuantity -> Integer
```

**Returns:** `Integer`

---

### GetStockEntitySelection {#getstockentityselection}


```4d
Function GetStockEntitySelection -> 4D.EntitySelection
```

**Returns:** `4D.EntitySelection`

---

### GetNewStockQuarantineStatus {#getnewstockquarantinestatus}


```4d
Function GetNewStockQuarantineStatus -> Boolean
```

**Returns:** `Boolean`

---

### GetQuarantineReason {#getquarantinereason}


```4d
Function GetQuarantineReason -> Text
```

**Returns:** `Text`

---

---

*Generated from Stock.4dm*
*Last updated: 2025-11-12T17:04:22.488Z*
