---
layout : default
title : Tools
parent : Classes
---
# Tools [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Tools.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

DataClass for injection moulding tool records, linking each tool to its product and tracking production parameters. Supports entity migration with linking enabled by tool number and provides UI-based tool creation linked to an existing product.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.762Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
    - [createForProduct](#createforproduct) → `cs.ToolsEntity` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns configuration for entity migration including linking settings and remote datastore selection

**Returns:** `Object`

---

#### createForProduct {#createforproduct}
 `[🖥️ local]`

```4d
Function createForProduct -> cs.ToolsEntity
```

Creates a new tool and product option through UI entry form, linking to an existing product

**Returns:** `cs.ToolsEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Tools](../Tables/Tools.md) - ORDA DataClass class for Tools table

### � Related Classes

- [ToolsEntity](ToolsEntity.md) - ORDA Entity class for Tools table

### � Forms

- [%2AToolEditor](../Forms/%2AToolEditor.md) - Data source for %2AToolEditor form
- [AddWorkRequest](../Forms/AddWorkRequest.md) - Data source for AddWorkRequest form
- [CapacityPlanning](../Forms/CapacityPlanning.md) - Data source for CapacityPlanning form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [EDIgenerator](../Forms/EDIgenerator.md) - Data source for EDIgenerator form
- [EquipmentProfiles](../Forms/EquipmentProfiles.md) - Data source for EquipmentProfiles form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [PackingLabour](../Forms/PackingLabour.md) - Data source for PackingLabour form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [Quality](../Forms/Quality.md) - Data source for Quality form
- [QualitySystemResults](../Forms/QualitySystemResults.md) - Data source for QualitySystemResults form
- [QualitySystemTolerances](../Forms/QualitySystemTolerances.md) - Data source for QualitySystemTolerances form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [ToolDisplay4](../Forms/ToolDisplay4.md) - Data source for ToolDisplay4 form
- [ToolDocuments](../Forms/ToolDocuments.md) - Data source for ToolDocuments form
- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form
- [ToolStandardsReview](../Forms/ToolStandardsReview.md) - Data source for ToolStandardsReview form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from Tools.4dm*
