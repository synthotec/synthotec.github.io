# BoxLabels

**Extends:** `DataClass`

## Table of Contents

### Functions

- [getMigrationSettings()](#getmigrationsettings)
- [getAvailableToPick()](#getavailabletopick)
- [checkPalletQuantity()](#checkpalletquantity)
- [getUsingScanner()](#getusingscanner)
- [getByUUID()](#getbyuuid)
- [GetBoxQuantity()](#getboxquantity)
- [restScannedBoxLabel()](#restscannedboxlabel)

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
Function getAvailableToPick($ProductEntity : cs.ProductEntity) -> cs.BoxLabelsSelection
```

**Returns:** `cs.BoxLabelsSelection`

---

### checkPalletQuantity {#checkpalletquantity}


```4d
Function checkPalletQuantity($WorksOrderEntity : cs.WorksOrderEntity; $RouteCardNumber : Integer)
```

---

### getUsingScanner {#getusingscanner}


```4d
Function getUsingScanner($ScannerObject : Object) -> cs.BoxLabelsEntity
```

**Returns:** `cs.BoxLabelsEntity`

---

### getByUUID {#getbyuuid}


```4d
Function getByUUID($UUID : Text) -> cs.BoxLabelsEntity
```

**Returns:** `cs.BoxLabelsEntity`

---

### GetBoxQuantity {#getboxquantity}
 `[exposed]`

```4d
Function GetBoxQuantity($BoxLabelID : Integer) -> Integer
```

**Returns:** `Integer`

---

### restScannedBoxLabel {#restscannedboxlabel}
 `[exposed]`

```4d
Function restScannedBoxLabel($RestPostDataObject : Object) -> Object
```

**Returns:** `Object`

---

---

*Generated from BoxLabels.4dm*
*Last updated: 2025-11-12T17:17:31.321Z*
