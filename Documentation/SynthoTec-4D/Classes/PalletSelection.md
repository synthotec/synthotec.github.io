---
layout : default
title : PalletSelection
parent : Classes
---
# PalletSelection [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PalletSelection.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

Entity selection of pallet records, providing a filter to retrieve pallets that are verified, located at a despatch location, and not yet assigned to any pick request.

**Extends:** `EntitySelection`

🕐 *Last updated: 2026-03-09T14:45:30.353Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getAvailable](#getavailable) → `cs.PalletSelection` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getAvailable {#getavailable}
 `[🖥️ local]`

```4d
Function getAvailable -> cs.PalletSelection
```

Returns verified pallets at despatch locations that are not assigned to any pick request

**Returns:** `cs.PalletSelection`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Pallet](../Tables/Pallet.md) - ORDA EntitySelection class for Pallet table

### � Related Classes

- [Pallet](Pallet.md) - ORDA DataClass class for Pallet table
- [PalletEntity](PalletEntity.md) - ORDA Entity class for Pallet table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [%2Atest](../Forms/%2Atest.md) - Data source for %2Atest form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [LocationManager](../Forms/LocationManager.md) - Data source for LocationManager form
- [NSKPalletIDs](../Forms/NSKPalletIDs.md) - Data source for NSKPalletIDs form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form
- [PalletTransfer](../Forms/PalletTransfer.md) - Data source for PalletTransfer form
- [Warehouse](../Forms/Warehouse.md) - Data source for Warehouse form

---

*Generated from PalletSelection.4dm*
