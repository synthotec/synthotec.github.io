---
layout : default
title : QRCode
parent : Classes
---
# QRCode [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/QRCode.4dm)

📊 **Overview:** 1 Constructor | 5 Functions | 2 Getters

🕐 *Last updated: 2025-11-19T18:12:03.553Z*

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

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BoxLabelID` | `Integer` | - | - |

---

#### fillPalletQR {#fillpalletqr}


```4d
Function fillPalletQR($PalletID : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PalletID` | `Integer` | - | - |

---

#### fillPrinterQR {#fillprinterqr}


```4d
Function fillPrinterQR($PrinterID : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PrinterID` | `Integer` | - | - |

---

#### getJson {#getjson}


```4d
Function getJson -> Text
```

**Returns:** `Text`

---

#### generate {#generate}


```4d
Function generate -> Picture
```

**Returns:** `Picture`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### BarcodeType {#barcodetype}
 `[🔍 get only]`

```4d
Function get BarcodeType -> Text
```

**Returns:** `Text`

---

#### PrimaryKey {#primarykey}
 `[🔍 get only]`

```4d
Function get PrimaryKey -> Integer
```

**Returns:** `Integer`

---

---

*Generated from QRCode.4dm*
