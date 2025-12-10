---
layout : default
title : Stock_Location
parent : Classes
---
# Stock_Location [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Stock_Location.4dm)

📊 **Overview:** 1 Functions | 3 Getters

**Extends:** `DataClass`

🕐 *Last updated: 2025-12-10T11:45:24.419Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getDefaultDespatchLocation](#getdefaultdespatchlocation) → `cs.Stock_LocationEntity` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [DefaultDespatchLocation](#defaultdespatchlocation) 🔍 → `cs.Stock_LocationEntity`
    - [DefaultPackingLocation](#defaultpackinglocation) 🔍 → `cs.Stock_LocationEntity`
    - [PartBoxStore](#partboxstore) 🔍 → `cs.Stock_LocationEntity`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getDefaultDespatchLocation {#getdefaultdespatchlocation}
 `[🖥️ local]`

```4d
Function getDefaultDespatchLocation -> cs.Stock_LocationEntity
```

**Returns:** `cs.Stock_LocationEntity`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### DefaultDespatchLocation {#defaultdespatchlocation}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DefaultDespatchLocation -> cs.Stock_LocationEntity
```

**Returns:** `cs.Stock_LocationEntity`

---

#### DefaultPackingLocation {#defaultpackinglocation}
 `[🔍 get only, 🖥️ local]`

```4d
Function get DefaultPackingLocation -> cs.Stock_LocationEntity
```

**Returns:** `cs.Stock_LocationEntity`

---

#### PartBoxStore {#partboxstore}
 `[🔍 get only, 🖥️ local]`

```4d
Function get PartBoxStore -> $Stock_LocationEntity : cs.Stock_LocationEntity
```

**Returns:** `cs.Stock_LocationEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Stock_Location](../Tables/Stock_Location.md) - ORDA DataClass class for Stock_Location table

### � Related Classes

- [Stock_LocationEntity](Stock_LocationEntity.md) - ORDA Entity class for Stock_Location table

### � Forms

- [%2AStockControl](../Forms/%2AStockControl.md) - Data source for %2AStockControl form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [EDIgenerator](../Forms/EDIgenerator.md) - Data source for EDIgenerator form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [PalletTransfer](../Forms/PalletTransfer.md) - Data source for PalletTransfer form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form
- [StockAtLocation](../Forms/StockAtLocation.md) - Data source for StockAtLocation form
- [StockMovements](../Forms/StockMovements.md) - Data source for StockMovements form

---

*Generated from Stock_Location.4dm*
