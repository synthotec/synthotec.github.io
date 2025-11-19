---
layout : default
title : PurchaseInfoEntity
parent : Classes
---
# PurchaseInfoEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PurchaseInfoEntity.4dm)

📊 **Overview:** 1 Functions | 2 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T18:12:03.543Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [createReceipt](#createreceipt) → `cs.PurchaseReceiptsEntity` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [OutstandingQuantity](#outstandingquantity) 🔍 → `Real`
    - [value](#value) 🔍 → `Real`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### createReceipt {#createreceipt}
 `[🖥️ local]`

```4d
Function createReceipt -> cs.PurchaseReceiptsEntity
```

**Returns:** `cs.PurchaseReceiptsEntity`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### OutstandingQuantity {#outstandingquantity}
 `[🔍 get only, 🖥️ local]`

```4d
Function get OutstandingQuantity -> Real
```

**Returns:** `Real`

---

#### value {#value}
 `[🔍 get only, 🖥️ local]`

```4d
Function get value -> Real
```

**Returns:** `Real`

---

## Related Items {#related-items}

### 🗂️ Tables

- [PurchaseInfo](../Tables/PurchaseInfo.md) - ORDA Entity class for PurchaseInfo table

### � Forms

- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [NominalCodes](../Forms/NominalCodes.md) - Data source for NominalCodes form
- [PurchaseOrders](../Forms/PurchaseOrders.md) - Data source for PurchaseOrders form

---

*Generated from PurchaseInfoEntity.4dm*
