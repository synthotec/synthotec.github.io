---
layout : default
title : BoxLabels
parent : Classes
---
# BoxLabels [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/BoxLabels.4dm)

📊 **Overview:** 7 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:11.021Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
    - [getAvailableToPick](#getavailabletopick) (1 param) → `cs.BoxLabelsSelection` 🖥️
    - [checkPalletQuantity](#checkpalletquantity) (2 params)
    - [getUsingScanner](#getusingscanner) (1 param) → `$BoxLabelsEntity : cs.BoxLabelsEntity`
    - [getByUUID](#getbyuuid) (1 param) → `cs.BoxLabelsEntity`
    - [GetBoxQuantity](#getboxquantity) (1 param) → `$BoxQuantity : Integer`
    - [restScannedBoxLabel](#restscannedboxlabel) (1 param) → `Object`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns configuration settings for entity migration including custom property formulas for ID and UUID

**Returns:** `Object`

---

#### getAvailableToPick {#getavailabletopick}
 `[🖥️ local]`

```4d
Function getAvailableToPick($ProductEntity : cs.ProductEntity) -> cs.BoxLabelsSelection
```

Returns boxes available for picking: in stock (v2+), not on pallet, not already pick-requested, matching product

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

Validates that parts packed on a route card do not exceed the configured pallet quantity, sends email alert if exceeded

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

Retrieves a box label entity using scanner data (UUID or BoxLabelID), validates works order matches

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

Finds and returns a box label entity by its UUID, returns Null if UUID is empty or not found

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

REST API endpoint: Returns the total quantity of parts in the specified box label

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

REST API endpoint: Processes scanned box label data and returns warehouse view data for mobile app

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [BoxLabels](../Tables/BoxLabels.md) - ORDA DataClass class for BoxLabels table

### � Related Classes

- [BoxLabelsEntity](BoxLabelsEntity.md) - ORDA Entity class for BoxLabels table

### � Forms

- [%2Atest](../Forms/%2Atest.md) - Data source for %2Atest form
- [%2Atest1](../Forms/%2Atest1.md) - Data source for %2Atest1 form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [NSKPalletIDs](../Forms/NSKPalletIDs.md) - Data source for NSKPalletIDs form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form
- [Warehouse](../Forms/Warehouse.md) - Data source for Warehouse form

---

*Generated from BoxLabels.4dm*
