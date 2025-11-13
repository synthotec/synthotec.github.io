---
layout : default
title : QRCode
parent : Classes
---
# QRCode

## Table of Contents

### Functions

- [constructor() [constructor]](#constructor)
- [fillBoxLabelsQR()](#fillboxlabelsqr)
- [fillPalletQR()](#fillpalletqr)
- [fillPrinterQR()](#fillprinterqr)
- [getJson()](#getjson)
- [generate()](#generate)
- [BarcodeType() [getter]](#barcodetype)
- [PrimaryKey() [getter]](#primarykey)

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($BarcodeType : Text; $PrimaryKey : Integer)
```

---

### fillBoxLabelsQR {#fillboxlabelsqr}


```4d
Function fillBoxLabelsQR($BoxLabelID : Integer)
```

---

### fillPalletQR {#fillpalletqr}


```4d
Function fillPalletQR($PalletID : Integer)
```

---

### fillPrinterQR {#fillprinterqr}


```4d
Function fillPrinterQR($PrinterID : Integer)
```

---

### getJson {#getjson}


```4d
Function getJson -> Text
```

**Returns:** `Text`

---

### generate {#generate}


```4d
Function generate -> Picture
```

**Returns:** `Picture`

---

### BarcodeType {#barcodetype}
 `[getter]`

```4d
Function BarcodeType -> Text
```

**Returns:** `Text`

---

### PrimaryKey {#primarykey}
 `[getter]`

```4d
Function PrimaryKey -> Integer
```

**Returns:** `Integer`

---

---

*Generated from QRCode.4dm*
*Last updated: 2025-11-13T00:30:42.441Z*
