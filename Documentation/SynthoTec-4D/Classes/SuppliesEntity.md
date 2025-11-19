---
layout : default
title : SuppliesEntity
parent : Classes
---
# SuppliesEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/SuppliesEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T18:10:07.740Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.SuppliesEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.SuppliesEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.SuppliesEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.SuppliesEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [Supplies](../Tables/Supplies.md) - ORDA Entity class for Supplies table

### � Related Classes

- [Supplies](Supplies.md) - ORDA DataClass class for Supplies table

### � Forms

- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [BOM_Packaging](../Forms/BOM_Packaging.md) - Data source for BOM_Packaging form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [SupplyInfo](../Forms/SupplyInfo.md) - Data source for SupplyInfo form
- [TransferSupply](../Forms/TransferSupply.md) - Data source for TransferSupply form

---

*Generated from SuppliesEntity.4dm*
