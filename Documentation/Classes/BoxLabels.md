---
layout : default
title : BoxLabels
parent : Classes
---
# BoxLabels

📊 **Overview:** 7 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T21:44:49.847Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (7):**

- [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [getAvailableToPick](#getavailabletopick) (1 param) → `cs.BoxLabelsSelection` 🖥️
- [checkPalletQuantity](#checkpalletquantity) (2 params)
- [getUsingScanner](#getusingscanner) (1 param) → `$BoxLabelsEntity : cs.BoxLabelsEntity`
- [getByUUID](#getbyuuid) (1 param) → `cs.BoxLabelsEntity`
- [GetBoxQuantity](#getboxquantity) (1 param) → `$BoxQuantity : Integer`
- [restScannedBoxLabel](#restscannedboxlabel) (1 param) → `Object`

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

**Returns:** `Object`

---

#### getAvailableToPick {#getavailabletopick}
 `[🖥️ local]`

```4d
Function getAvailableToPick($ProductEntity : cs.ProductEntity) -> cs.BoxLabelsSelection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductEntity` | `cs.ProductEntity` | - | - |

**Returns:** `cs.BoxLabelsSelection`

---

#### checkPalletQuantity {#checkpalletquantity}


```4d
Function checkPalletQuantity($WorksOrderEntity : cs.WorksOrderEntity; $RouteCardNumber : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$WorksOrderEntity` | `cs.WorksOrderEntity` | - | - |
| `$RouteCardNumber` | `Integer` | - | - |

---

#### getUsingScanner {#getusingscanner}


```4d
Function getUsingScanner($ScannerObject : Object) -> $BoxLabelsEntity : cs.BoxLabelsEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ScannerObject` | `Object` | - | - |

**Returns:** `cs.BoxLabelsEntity`

---

#### getByUUID {#getbyuuid}


```4d
Function getByUUID($UUID : Text) -> cs.BoxLabelsEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$UUID` | `Text` | - | - |

**Returns:** `cs.BoxLabelsEntity`

---

#### GetBoxQuantity {#getboxquantity}


```4d
Function GetBoxQuantity($BoxLabelID : Integer) -> $BoxQuantity : Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BoxLabelID` | `Integer` | - | - |

**Returns:** `Integer`

---

#### restScannedBoxLabel {#restscannedboxlabel}


```4d
Function restScannedBoxLabel($RestPostDataObject : Object) -> Object
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## 🔗 Related Items

### 🗂️ Tables

- [BoxLabels](../Tables/BoxLabels.md) - Source table for this ORDA class
- [BoxLabels](../Tables/BoxLabels.md) - Database table storing BoxLabels records

### � Related Classes

- [BoxLabels](BoxLabels.md) - ORDA DataClass class for BoxLabels table
- [BoxLabelsEntity](BoxLabelsEntity.md) - ORDA Entity class for BoxLabels table

---

*Generated from BoxLabels.4dm*
