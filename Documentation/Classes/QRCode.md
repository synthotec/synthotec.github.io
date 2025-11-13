---
layout : default
title : QRCode
parent : Classes
---
# QRCode

📊 **Overview:** 1 Constructor | 5 Functions | 2 Getters

🕐 *Last updated: 2025-11-13T16:07:43.036Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Regular Functions (5):**

- [fillBoxLabelsQR](#fillboxlabelsqr) (1 param)
- [fillPalletQR](#fillpalletqr) (1 param)
- [fillPrinterQR](#fillprinterqr) (1 param)
- [getJson](#getjson) → `Text`
- [generate](#generate) → `Picture`

**🔍 Getters (2):**

- [BarcodeType](#barcodetype) → `Text`
- [PrimaryKey](#primarykey) → `Integer`

---

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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

### 🔍 Getters

#### BarcodeType {#barcodetype}
 `[🔍 getter]`

```4d
Function BarcodeType -> Text
```

**Returns:** `Text`

---

#### PrimaryKey {#primarykey}
 `[🔍 getter]`

```4d
Function PrimaryKey -> Integer
```

**Returns:** `Integer`

---

---

*Generated from QRCode.4dm*
