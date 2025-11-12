# Pallet

**Extends:** `DataClass`

## Table of Contents

### Functions

- [getMigrationSettings()](#getmigrationsettings)
- [getAvailableToPick()](#getavailabletopick)
- [getUsingScanner()](#getusingscanner)
- [Create()](#create)
- [Verify()](#verify)
- [Print()](#print)
- [Delete()](#delete)
- [restLoadPalletList()](#restloadpalletlist)
- [restAddToPallet()](#restaddtopallet)
- [restCompletePallet()](#restcompletepallet)
- [restVerifyPallet()](#restverifypallet)
- [restLocatePallet()](#restlocatepallet)
- [restDeletePallet()](#restdeletepallet)
- [restReassignLocation()](#restreassignlocation)
- [restLoadPallet()](#restloadpallet)

---

## Functions

### getMigrationSettings {#getmigrationsettings}
 `[local]`

```4d
Function getMigrationSettings -> Object
```

**Returns:** `Object`

---

### getAvailableToPick {#getavailabletopick}
 `[local]`

```4d
Function getAvailableToPick($ProductEntity : cs.ProductEntity) -> cs.PalletSelection
```

return This.query("Verified=True && Location IN :1 && OrderPickRequestEntity=Null && ProductEntity.ID=:2"; ds.Stock_Location.query("DespatchLocation=True").ID; $ProductEntity.ID)

**Returns:** `cs.PalletSelection`

---

### getUsingScanner {#getusingscanner}


```4d
Function getUsingScanner($ScannerObject : Object; $ScannerText : Text) -> cs.PalletEntity
```

**Returns:** `cs.PalletEntity`

---

### Create {#create}
 `[exposed]`

```4d
Function Create($BoxLabelIDCollection : Collection; $StaffID : Integer) -> Object
```

**Returns:** `Object`

---

### Verify {#verify}
 `[exposed]`

```4d
Function Verify($PalletID : Integer; $BoxLabelID : Integer; $StaffID : Integer) -> Object
```

**Returns:** `Object`

---

### Print {#print}
 `[exposed]`

```4d
Function Print($PalletID : Integer; $Printer : Text) -> Object
```

**Returns:** `Object`

---

### Delete {#delete}
 `[exposed]`

```4d
Function Delete($PalletID : Integer) -> Object
```

**Returns:** `Object`

---

### restLoadPalletList {#restloadpalletlist}
 `[exposed]`

```4d
Function restLoadPalletList($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restAddToPallet {#restaddtopallet}
 `[exposed]`

```4d
Function restAddToPallet($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restCompletePallet {#restcompletepallet}
 `[exposed]`

```4d
Function restCompletePallet($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restVerifyPallet {#restverifypallet}
 `[exposed]`

```4d
Function restVerifyPallet($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restLocatePallet {#restlocatepallet}
 `[exposed]`

```4d
Function restLocatePallet($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restDeletePallet {#restdeletepallet}
 `[exposed]`

```4d
Function restDeletePallet($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restReassignLocation {#restreassignlocation}
 `[exposed]`

```4d
Function restReassignLocation($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

### restLoadPallet {#restloadpallet}
 `[exposed]`

```4d
Function restLoadPallet($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

---

*Generated from Pallet.4dm*
*Last updated: 2025-11-12T17:04:22.001Z*
