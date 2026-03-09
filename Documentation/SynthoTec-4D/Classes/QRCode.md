---
layout : default
title : QRCode
parent : Classes
---
# QRCode [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/QRCode.4dm)

📊 **Overview:** 1 Constructor | 5 Functions | 2 Getters

## 📝 Description

Generates structured QR code data objects for different barcode types (box label, pallet, printer) by looking up the matching entity and populating the relevant fields. Used in the warehouse and printing subsystems.

🕐 *Last updated: 2026-03-09T14:45:30.908Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [fillBoxLabelsQR](#fillboxlabelsqr) (1 param)
    - [fillPalletQR](#fillpalletqr) (1 param)
    - [fillPrinterQR](#fillprinterqr) (1 param)
    - [getJson](#getjson) → `Text`
    - [generate](#generate) → `Picture`
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [BarcodeType](#barcodetype) 🔍 → `Text`
    - [PrimaryKey](#primarykey) 🔍 → `Integer`

---

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($BarcodeType : Text; $PrimaryKey : Integer)
```

Initializes a QR code object and populates it based on the barcode type and primary key

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BarcodeType` | `Text` | - | - |
| `$PrimaryKey` | `Integer` | - | - |

---

## Functions {#functions}

### Regular Functions

#### fillBoxLabelsQR {#fillboxlabelsqr}


```4d
Function fillBoxLabelsQR($BoxLabelID : Integer)
```

Populates QR code data from a box label entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BoxLabelID` | `Integer` | - | - |

---

#### fillPalletQR {#fillpalletqr}


```4d
Function fillPalletQR($PalletID : Integer)
```

Populates QR code data from a pallet entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PalletID` | `Integer` | - | - |

---

#### fillPrinterQR {#fillprinterqr}


```4d
Function fillPrinterQR($PrinterID : Integer)
```

Populates QR code data from a printer entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PrinterID` | `Integer` | - | - |

---

#### getJson {#getjson}


```4d
Function getJson -> Text
```

Returns the QR code data as a JSON string

**Returns:** `Text`

---

#### generate {#generate}


```4d
Function generate -> Picture
```

Generates and returns a QR code picture from the stored data

**Returns:** `Picture`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### BarcodeType {#barcodetype}
 `[🔍 get only]`

```4d
Function get BarcodeType -> Text
```

Returns the type of barcode this QR code represents

**Returns:** `Text`

---

#### PrimaryKey {#primarykey}
 `[🔍 get only]`

```4d
Function get PrimaryKey -> Integer
```

Returns the primary key ID of the entity this QR code represents

**Returns:** `Integer`

---

---

*Generated from QRCode.4dm*
