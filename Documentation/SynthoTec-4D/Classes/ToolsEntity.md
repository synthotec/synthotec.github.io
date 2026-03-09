---
layout : default
title : ToolsEntity
parent : Classes
---
# ToolsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolsEntity.4dm)

📊 **Overview:** 2 Functions | 2 Getters

## 📝 Description

Entity representing an injection moulding tool record, with a Tool_ID primary key alias, a computed count of unacknowledged temperature sensor exceptions (for dashboard alerting), and detailed migration rules covering 50+ production parameters (cycle time, weights, approvals, images, concessions, etc.).

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:31.794Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [NextToolChangeText](#nexttoolchangetext) 🔍 → `Text`
    - [PartsPerHour](#partsperhour) 🔍 → `Real`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ToolsEntity) -> $Collection : Collection
```

Returns collection of EntityMigrationRule objects defining how to merge this tool record with the remote datastore

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ToolsEntity)
```

Syncs migration selections for tool entity relations (approvals, maintenance tasks, logs, etc) with remote entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolsEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### NextToolChangeText {#nexttoolchangetext}
 `[🔍 get only]`

```4d
Function get NextToolChangeText -> Text
```

Returns formatted next scheduled tool change date; or "Not Planned" if no future tool changes

**Returns:** `Text`

---

#### PartsPerHour {#partsperhour}
 `[🔍 get only]`

```4d
Function get PartsPerHour -> Real
```

Returns theoretical parts per hour (impressions per cycle × 3600 seconds); returns 0 if cycle time is not set

**Returns:** `Real`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Tools](../Tables/Tools.md) - ORDA Entity class for Tools table

### � Related Classes

- [Tools](Tools.md) - ORDA DataClass class for Tools table

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

*Generated from ToolsEntity.4dm*
