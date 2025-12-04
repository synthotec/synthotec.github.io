---
layout : default
title : Tools
parent : Tables
---
# Tools

📊 **Overview:** 139 Fields | 10 Indexes | 2 Many-to-One Relations | 12 One-to-Many Relations

## 📝 Description

🗨️ Master data table for injection molding tools/dies. Stores tool specifications, maintenance history, temperature settings, and production parameters. Links to Products and tracks tool lifecycle.

## ℹ️ Table Information

- **Table ID:** 2
- **UUID:** 730DDB789A822A45A2769798BE8BF8C3
- **Primary Key:** 🔑 `Tool_ID`
- **Generated:** 🕐 2025-12-04T14:33:31Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (139)
- [🔍 Indexes](#-indexes) (10)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (12)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (26)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| NextUniqueLabelID_l | `Long Integer` | 🚫 Not Null | - |
| Approved | `Boolean` | 🚫 Not Null | - |
| Short Name | `String` | 🚫 Not Null, ���️ Hidden | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| 🔑 **Tool_ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null, ��� Not Modifiable | - |
| PartNo | `String` (30) | 🚫 Not Null | - |
| ShortName | `String` (25) | 🚫 Not Null, ���️ Hidden | - |
| Machine_Type | `String` | 🚫 Not Null | - |
| NumOfRows | `Long Integer` | 🚫 Not Null | - |
| Pallet_Pic | `Picture` | 🚫 Not Null | - |
| Setup_Sheet | `Boolean` | 🚫 Not Null | - |
| OperatorRequired | `Boolean` | 🚫 Not Null | - |
| Robot_Prg_No | `String` (255) | 🚫 Not Null | - |
| Pallet_Type_m | `String` (255) | 🚫 Not Null | - |
| Tool_No | `String` (10) | ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Impressions | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Date Created | `Date` | 🚫 Not Null, 🔒 Not Enterable | - |
| Box_Per_Pallet | `Integer` | 🚫 Not Null | - |
| Boxes_Per_M_Pallet | `Integer` | 🚫 Not Null | - |
| Archive | `Boolean` | 🚫 Not Null | - |
| CycleTimeSecs | `Real` | ⚠️ Required, 🚫 Not Null | - |
| PartWtGrams | `Real` | ⚠️ Required, 🚫 Not Null | - |
| RunnerWtGrams | `Real` | 🚫 Not Null | - |
| Regrind_MaxPercent | `Real` | 🚫 Not Null | - |
| Packed_Per_Hour | `Long Integer` | 🚫 Not Null | - |
| Mandrells_per_Pallet | `Integer` | 🚫 Not Null | - |
| Packing Box | `String` (20) | 🚫 Not Null, ���️ Hidden | - |
| Dry_Weight | `Real` | 🚫 Not Null | - |
| If on Concess | `Boolean` | 🚫 Not Null | - |
| If Concess by N | `Boolean` | 🚫 Not Null | - |
| Total No Conces | `Long Integer` | 🚫 Not Null | - |
| No Concess Supp | `Long Integer` | 🚫 Not Null | - |
| Concess End Dat | `Date` | 🚫 Not Null | - |
| DryWeightText | `String` | 🚫 Not Null | - |
| ReasonToolOffsite_txt | `String` | 🚫 Not Null | - |
| IsToolOffsite_b | `Boolean` | 🚫 Not Null | - |
| DateToolDueBack_d | `Date` | 🚫 Not Null | - |
| TimePerPallet | `Integer` | 🚫 Not Null | - |
| Picture | `Picture` | 🚫 Not Null | - |
| Prodn Quan Min | `Long Integer` | 🚫 Not Null | - |
| Production_Mandrell | `String` (255) | 🚫 Not Null | - |
| Tool_Notes | `String` | 🚫 Not Null | - |
| Conditioned | `Boolean` | 🚫 Not Null | - |
| Type | `Integer` | 🚫 Not Null | - |
| Grey box Quan | `Long Integer` | 🚫 Not Null, ���️ Hidden | - |
| Cages_per_Mandrell | `Integer` | 🚫 Not Null | - |
| Concession No | `String` (20) | 🚫 Not Null | - |
| Customer Label | `String` (25) | 🚫 Not Null | - |
| Additional_text_4_label | `String` | 🚫 Not Null | - |
| Nozzle | `String` (10) | 🚫 Not Null | - |
| Separator | `Integer` | 🚫 Not Null | - |
| Prodn Quan Max | `Long Integer` | 🚫 Not Null | - |
| Location | `String` (30) | 🚫 Not Null | - |
| Tool Mod | `String` (10) | 🚫 Not Null | - |
| Initial Cust | `String` (3) | 🚫 Not Null | - |
| Main Tool | `Boolean` | 🚫 Not Null | - |
| Additional_text | `String` | 🚫 Not Null | - |
| UseAddressLabels_b | `Boolean` | 🚫 Not Null | - |
| UseUniqueIDLabels_b | `Boolean` | 🚫 Not Null | - |
| LabelChoice_s | `String` (35) | ⚠️ Required, 🚫 Not Null | - |
| UseBagLabel_b | `Boolean` | 🚫 Not Null | - |
| UseExtraID_b | `Boolean` | 🚫 Not Null | - |
| UseLogisticslabel_b | `Boolean` | 🚫 Not Null | - |
| NextUniqueIDLogistics_l | `Long Integer` | 🚫 Not Null | - |
| Final_Customer | `String` (35) | 🚫 Not Null | - |
| Weight_kitlabel | `Real` | 🚫 Not Null | - |
| Kit_ProductID | `String` (30) | 🚫 Not Null | - |
| Kit_Quantity | `Long Integer` | 🚫 Not Null | - |
| Mandrel_OD | `Real` | 🚫 Not Null | - |
| NumOfLayers | `Long Integer` | 🚫 Not Null | - |
| BagSealingMethod | `String` (255) | 🚫 Not Null | - |
| PackedInColumns | `Boolean` | 🚫 Not Null | - |
| RC_Sub_Sequence | `Long Integer` | 🚫 Not Null | - |
| RC_Additional_Seq | `Boolean` | 🚫 Not Null | - |
| RC_Barcode | `Boolean` | 🚫 Not Null | - |
| x3_sequence_packsheet | `Boolean` | 🚫 Not Null | - |
| x4_sequence_packsheet | `Boolean` | 🚫 Not Null | - |
| PackagingInstructionIssueDate | `Date` | 🚫 Not Null | - |
| PackagingInstructionIssueName | `String` (255) | 🚫 Not Null | - |
| identifier_address | `String` (2) | 🚫 Not Null | - |
| No_metalpallets_per_box | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| two_boxnos | `Boolean` | 🚫 Not Null | - |
| qty_delivered_flag | `Boolean` | 🚫 Not Null | - |
| qty_pricechange | `Long Integer` | 🚫 Not Null | - |
| packrange_max | `Long Integer` | 🚫 Not Null | - |
| AQP | `Boolean` | 🚫 Not Null | - |
| x2_uniqueIDlabels | `Boolean` | 🚫 Not Null | - |
| DateChanged | `Date` | 🚫 Not Null | - |
| PackagingInstructionIssueLevel | `String` (255) | 🚫 Not Null | - |
| IsHandLoaded | `Boolean` | 🚫 Not Null | - |
| OddLayerQuantity | `Long Integer` | 🚫 Not Null | - |
| SmallSide | `Boolean` | 🚫 Not Null | - |
| LargeSide | `Boolean` | 🚫 Not Null | - |
| AlternatingLayerQuantA | `Long Integer` | 🚫 Not Null | - |
| AlternatingLayerQuantB | `Long Integer` | 🚫 Not Null | - |
| ScalesFixedQuant | `Long Integer` | 🚫 Not Null | - |
| ExtraPackInfo | `String` | 🚫 Not Null | - |
| LabelOrigin | `Boolean` | 🚫 Not Null | - |
| QRCode | `Boolean` | 🚫 Not Null | - |
| Amber | `Boolean` | 🚫 Not Null | - |
| RunsSinceApproval | `Integer` | 🚫 Not Null | - |
| AmberCheckPercent | `Integer` | 🚫 Not Null | - |
| AmberManual | `Boolean` | 🚫 Not Null | - |
| AmberManualWhen | `Date` | 🚫 Not Null | - |
| AmberManualWho | `String` (255) | 🚫 Not Null | - |
| AmberPQITriggered | `Boolean` | 🚫 Not Null | - |
| RCText | `String` (255) | 🚫 Not Null | - |
| ForeCast2015 | `Long Integer` | 🚫 Not Null | - |
| ForeCast2015Update | `Date` | 🚫 Not Null | - |
| ProductName | `String` (255) | 🚫 Not Null | - |
| PicBlob | `BLOB Scalar` | 🚫 Not Null | - |
| PicBlobTxt | `String` | 🚫 Not Null | - |
| LogisticsPrefix | `String` (255) | 🚫 Not Null | - |
| DataMatrix | `Boolean` | 🚫 Not Null | - |
| Regrind | `Boolean` | 🚫 Not Null | - |
| RegrindComments | `String` (255) | 🚫 Not Null | - |
| NotifyQuality | `Boolean` | 🚫 Not Null | - |
| NotifyReason | `String` (255) | 🚫 Not Null | - |
| ToolReady | `Boolean` | 🚫 Not Null | - |
| ToolOffsite | `Boolean` | 🚫 Not Null | - |
| StatusUpdated | `String` (255) | 🚫 Not Null | - |
| ToolDueDate | `Date` | 🚫 Not Null | - |
| PlanningWheelCycle | `Real` | 🚫 Not Null | - |
| PlanningWheelHours | `Real` | 🚫 Not Null | - |
| HotHalfID | `Long Integer` | 🚫 Not Null | - |
| HotHalfBooked | `Boolean` | 🚫 Not Null | - |
| AmberTriggerTime | `String` (255) | 🚫 Not Null | - |
| NewCalcedPartWeight | `Real` | 🚫 Not Null | - |
| MaintenanceCycleTrigger | `Long Integer` | 🚫 Not Null | - |
| UsageWarningDays | `Long Integer` | 🚫 Not Null | - |
| ExtraSideLabel | `Boolean` | 🚫 Not Null | - |
| QRtype | `Integer` | 🚫 Not Null | - |
| RequiresChecking | `Boolean` | - | - |
| TemperatureTargetMin | `Real` | 🚫 Not Null | - |
| TemperatureTargetMax | `Real` | 🚫 Not Null | - |
| RobotHeads | `String` (255) | - | - |
| MigrationID | `Long Integer` | - | - |
| ToolNoticeObject | `Object` | - | - |
| ProductionHoldObject | `Object` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `MigrationID` | Keywords | regular | - |
| `PartNo` | Keywords | regular | - |
| `Archive` | Keywords | regular | - |
| `ShortName` | Keywords | regular | - |
| `two_boxnos` | Keywords | regular | - |
| `HotHalfID` | Keywords | regular | - |
| `Tool_No` | Keywords | regular | - |
| `ProductID` | Keywords | regular | - |
| `HotHalfBooked` | Keywords | regular | - |
| `Tool_ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |
| `HotHalfEntity` | [HotHalfs](HotHalfs.md) | `HotHalfID` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `ToolID` → `Tool_ID` | Active | - |
| `NonConformanceSelection` | [NonConformance](NonConformance.md) | `Tool_ID` → `Tool_ID` | Active | - |
| `ToolLogSelection` | [ToolLog](ToolLog.md) | `Tool_ID` → `Tool_ID` | Active | - |
| `ApprovalsSelection` | [Approvals](Approvals.md) | `ToolID` → `Tool_ID` | Active | - |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `ToolID` → `Tool_ID` | Active | - |
| `WorkRequestsSelection` | [WorkRequests](WorkRequests.md) | `ToolID` → `Tool_ID` | Active | - |
| `ToolMaintenanceLogSelection` | [ToolMaintenanceLog](ToolMaintenanceLog.md) | `ToolID` → `Tool_ID` | Active | - |
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `ToolID` → `Tool_ID` | Active | - |
| `ToolDocumentSelection` | [ToolDocument](ToolDocument.md) | `ToolID` → `Tool_ID` | Active | - |
| `PlanningWheelSelection` | [PlanningWheel](PlanningWheel.md) | `ToolID` → `Tool_ID` | Active | - |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Tool ID` → `Tool_ID` | Active | - |
| `ToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `ToolID` → `Tool_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Tools](../Classes/Tools.md) - ORDA DataClass class for Tools table
- [ToolsEntity](../Classes/ToolsEntity.md) - ORDA Entity class for Tools table

### 📄 Forms

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

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:33:31Z*
