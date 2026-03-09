---
layout : default
title : MaterialStock
parent : Classes
---
# MaterialStock [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MaterialStock.4dm)

📊 **Overview:** 5 Functions

## 📝 Description

DataClass for material stock quantity records by material and location. Provides a function to zero out stock not counted in the latest stock take, logging each adjustment for traceability.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.043Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [removeUncountedStock](#removeuncountedstock)
    - [restLoadMaterialStock](#restloadmaterialstock) (1 param) → `Object`
    - [restAssignToMaterialCheck](#restassigntomaterialcheck) (1 param) → `Object`
    - [restUpdateQuantity](#restupdatequantity) (1 param) → `Object`
    - [restLocateMaterialStock](#restlocatematerialstock) (1 param) → `Object`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### removeUncountedStock {#removeuncountedstock}


```4d
Function removeUncountedStock
```

Zeroes quantity of all non-zero material stock not found in the latest stock take and logs each adjustment

---

#### restLoadMaterialStock {#restloadmaterialstock}


```4d
Function restLoadMaterialStock($RestPostDataObject : Object) -> Object
```

REST endpoint to load material stock details in warehouse mobile app, with location assignment options

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restAssignToMaterialCheck {#restassigntomaterialcheck}


```4d
Function restAssignToMaterialCheck($RestPostDataObject : Object) -> Object
```

REST endpoint to assign a scanned material stock item to a machine material check on a running works order

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restUpdateQuantity {#restupdatequantity}


```4d
Function restUpdateQuantity($RestPostDataObject : Object) -> Object
```

REST endpoint to update quantity of a material stock record via mobile app prompt

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restLocateMaterialStock {#restlocatematerialstock}


```4d
Function restLocateMaterialStock($RestPostDataObject : Object) -> Object
```

REST endpoint to locate and assign material stock to a location; processes QR code scan or manual location entry

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [MaterialStock](../Tables/MaterialStock.md) - ORDA DataClass class for MaterialStock table

### � Related Classes

- [MaterialStockEntity](MaterialStockEntity.md) - ORDA Entity class for MaterialStock table

### � Forms

- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from MaterialStock.4dm*
