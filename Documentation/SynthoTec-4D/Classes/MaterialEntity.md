---
layout : default
title : MaterialEntity
parent : Classes
---
# MaterialEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MaterialEntity.4dm)

📊 **Overview:** 3 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T18:12:03.030Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMaterialsUsingThis](#getmaterialsusingthis) → `cs.MaterialSelection`
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [HasMigrationID](#hasmigrationid) 🔍 → `Boolean`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### getMaterialsUsingThis {#getmaterialsusingthis}


```4d
Function getMaterialsUsingThis -> cs.MaterialSelection
```

**Returns:** `cs.MaterialSelection`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.MaterialEntity) -> $Collection : Collection
```

////////////////////////////////////////////////////////////////////////////////////////

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.MaterialEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.MaterialEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.MaterialEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Material](../Tables/Material.md) - ORDA Entity class for Material table

### � Related Classes

- [Material](Material.md) - ORDA DataClass class for Material table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [%2AToolEditor](../Forms/%2AToolEditor.md) - Data source for %2AToolEditor form
- [BOM](../Forms/BOM.md) - Data source for BOM form
- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [BOM_Output](../Forms/BOM_Output.md) - Data source for BOM_Output form
- [BOM_Packaging](../Forms/BOM_Packaging.md) - Data source for BOM_Packaging form
- [ChangeMaterial](../Forms/ChangeMaterial.md) - Data source for ChangeMaterial form
- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [Materials](../Forms/Materials.md) - Data source for Materials form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [SupplyInfo](../Forms/SupplyInfo.md) - Data source for SupplyInfo form

---

*Generated from MaterialEntity.4dm*
