---
layout : default
title : Tools
parent : Tables
---
# Tools

📊 **Overview:** 139 Fields | 10 Indexes | 2 Many-to-One Relations | 12 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 2
- **UUID:** 730DDB789A822A45A2769798BE8BF8C3
- **Primary Key:** 🔑 `Tool_ID`
- **Generated:** 🕐 2025-11-13T23:17:43Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (139)
- [🔍 Indexes](#-indexes) (10)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (12)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| NextUniqueLabelID_l | `Date` | 🚫 Not Null | - |
| Approved | `Real` | 🚫 Not Null | - |
| Short Name | `String` | 🚫 Not Null, ���️ Hidden | - |
| ProductID | `Date` | 🚫 Not Null | - |
| 🔑 **Tool_ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null, ��� Not Modifiable | - |
| PartNo | `String` (30) | 🚫 Not Null | - |
| ShortName | `String` (25) | 🚫 Not Null, ���️ Hidden | - |
| Machine_Type | `String` | 🚫 Not Null | - |
| NumOfRows | `Date` | 🚫 Not Null | - |
| Pallet_Pic | `Picture` | 🚫 Not Null | - |
| Setup_Sheet | `Real` | 🚫 Not Null | - |
| OperatorRequired | `Real` | 🚫 Not Null | - |
| Robot_Prg_No | `String` (255) | 🚫 Not Null | - |
| Pallet_Type_m | `String` (255) | 🚫 Not Null | - |
| Tool_No | `String` (10) | ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Impressions | `Picture` | ⚠️ Required, 🚫 Not Null | - |
| Date Created | `Integer` | 🚫 Not Null, 🔒 Not Enterable | - |
| Box_Per_Pallet | `Picture` | 🚫 Not Null | - |
| Boxes_Per_M_Pallet | `Picture` | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |
| CycleTimeSecs | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| PartWtGrams | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| RunnerWtGrams | `Boolean` | 🚫 Not Null | - |
| Regrind_MaxPercent | `Boolean` | 🚫 Not Null | - |
| Packed_Per_Hour | `Date` | 🚫 Not Null | - |
| Mandrells_per_Pallet | `Picture` | 🚫 Not Null | - |
| Packing Box | `String` (20) | 🚫 Not Null, ���️ Hidden | - |
| Dry_Weight | `Boolean` | 🚫 Not Null | - |
| If on Concess | `Real` | 🚫 Not Null | - |
| If Concess by N | `Real` | 🚫 Not Null | - |
| Total No Conces | `Date` | 🚫 Not Null | - |
| No Concess Supp | `Date` | 🚫 Not Null | - |
| Concess End Dat | `Integer` | 🚫 Not Null | - |
| DryWeightText | `String` | 🚫 Not Null | - |
| ReasonToolOffsite_txt | `String` | 🚫 Not Null | - |
| IsToolOffsite_b | `Real` | 🚫 Not Null | - |
| DateToolDueBack_d | `Integer` | 🚫 Not Null | - |
| TimePerPallet | `Picture` | 🚫 Not Null | - |
| Picture | `Picture` | 🚫 Not Null | - |
| Prodn Quan Min | `Date` | 🚫 Not Null | - |
| Production_Mandrell | `String` (255) | 🚫 Not Null | - |
| Tool_Notes | `String` | 🚫 Not Null | - |
| Conditioned | `Real` | 🚫 Not Null | - |
| Type | `Picture` | 🚫 Not Null | - |
| Grey box Quan | `Date` | 🚫 Not Null, ���️ Hidden | - |
| Cages_per_Mandrell | `Picture` | 🚫 Not Null | - |
| Concession No | `String` (20) | 🚫 Not Null | - |
| Customer Label | `String` (25) | 🚫 Not Null | - |
| Additional_text_4_label | `String` | 🚫 Not Null | - |
| Nozzle | `String` (10) | 🚫 Not Null | - |
| Separator | `Picture` | 🚫 Not Null | - |
| Prodn Quan Max | `Date` | 🚫 Not Null | - |
| Location | `String` (30) | 🚫 Not Null | - |
| Tool Mod | `String` (10) | 🚫 Not Null | - |
| Initial Cust | `String` (3) | 🚫 Not Null | - |
| Main Tool | `Real` | 🚫 Not Null | - |
| Additional_text | `String` | 🚫 Not Null | - |
| UseAddressLabels_b | `Real` | 🚫 Not Null | - |
| UseUniqueIDLabels_b | `Real` | 🚫 Not Null | - |
| LabelChoice_s | `String` (35) | ⚠️ Required, 🚫 Not Null | - |
| UseBagLabel_b | `Real` | 🚫 Not Null | - |
| UseExtraID_b | `Real` | 🚫 Not Null | - |
| UseLogisticslabel_b | `Real` | 🚫 Not Null | - |
| NextUniqueIDLogistics_l | `Date` | 🚫 Not Null | - |
| Final_Customer | `String` (35) | 🚫 Not Null | - |
| Weight_kitlabel | `Boolean` | 🚫 Not Null | - |
| Kit_ProductID | `String` (30) | 🚫 Not Null | - |
| Kit_Quantity | `Date` | 🚫 Not Null | - |
| Mandrel_OD | `Boolean` | 🚫 Not Null | - |
| NumOfLayers | `Date` | 🚫 Not Null | - |
| BagSealingMethod | `String` (255) | 🚫 Not Null | - |
| PackedInColumns | `Real` | 🚫 Not Null | - |
| RC_Sub_Sequence | `Date` | 🚫 Not Null | - |
| RC_Additional_Seq | `Real` | 🚫 Not Null | - |
| RC_Barcode | `Real` | 🚫 Not Null | - |
| x3_sequence_packsheet | `Real` | 🚫 Not Null | - |
| x4_sequence_packsheet | `Real` | 🚫 Not Null | - |
| PackagingInstructionIssueDate | `Integer` | 🚫 Not Null | - |
| PackagingInstructionIssueName | `String` (255) | 🚫 Not Null | - |
| identifier_address | `String` (2) | 🚫 Not Null | - |
| No_metalpallets_per_box | `Picture` | ⚠️ Required, 🚫 Not Null | - |
| two_boxnos | `Real` | 🚫 Not Null | - |
| qty_delivered_flag | `Real` | 🚫 Not Null | - |
| qty_pricechange | `Date` | 🚫 Not Null | - |
| packrange_max | `Date` | 🚫 Not Null | - |
| AQP | `Real` | 🚫 Not Null | - |
| x2_uniqueIDlabels | `Real` | 🚫 Not Null | - |
| DateChanged | `Integer` | 🚫 Not Null | - |
| PackagingInstructionIssueLevel | `String` (255) | 🚫 Not Null | - |
| IsHandLoaded | `Real` | 🚫 Not Null | - |
| OddLayerQuantity | `Date` | 🚫 Not Null | - |
| SmallSide | `Real` | 🚫 Not Null | - |
| LargeSide | `Real` | 🚫 Not Null | - |
| AlternatingLayerQuantA | `Date` | 🚫 Not Null | - |
| AlternatingLayerQuantB | `Date` | 🚫 Not Null | - |
| ScalesFixedQuant | `Date` | 🚫 Not Null | - |
| ExtraPackInfo | `String` | 🚫 Not Null | - |
| LabelOrigin | `Real` | 🚫 Not Null | - |
| QRCode | `Real` | 🚫 Not Null | - |
| Amber | `Real` | 🚫 Not Null | - |
| RunsSinceApproval | `Picture` | 🚫 Not Null | - |
| AmberCheckPercent | `Picture` | 🚫 Not Null | - |
| AmberManual | `Real` | 🚫 Not Null | - |
| AmberManualWhen | `Integer` | 🚫 Not Null | - |
| AmberManualWho | `String` (255) | 🚫 Not Null | - |
| AmberPQITriggered | `Real` | 🚫 Not Null | - |
| RCText | `String` (255) | 🚫 Not Null | - |
| ForeCast2015 | `Date` | 🚫 Not Null | - |
| ForeCast2015Update | `Integer` | 🚫 Not Null | - |
| ProductName | `String` (255) | 🚫 Not Null | - |
| PicBlob | `Unknown (18)` | 🚫 Not Null | - |
| PicBlobTxt | `String` | 🚫 Not Null | - |
| LogisticsPrefix | `String` (255) | 🚫 Not Null | - |
| DataMatrix | `Real` | 🚫 Not Null | - |
| Regrind | `Real` | 🚫 Not Null | - |
| RegrindComments | `String` (255) | 🚫 Not Null | - |
| NotifyQuality | `Real` | 🚫 Not Null | - |
| NotifyReason | `String` (255) | 🚫 Not Null | - |
| ToolReady | `Real` | 🚫 Not Null | - |
| ToolOffsite | `Real` | 🚫 Not Null | - |
| StatusUpdated | `String` (255) | 🚫 Not Null | - |
| ToolDueDate | `Integer` | 🚫 Not Null | - |
| PlanningWheelCycle | `Boolean` | 🚫 Not Null | - |
| PlanningWheelHours | `Boolean` | 🚫 Not Null | - |
| HotHalfID | `Date` | 🚫 Not Null | - |
| HotHalfBooked | `Real` | 🚫 Not Null | - |
| AmberTriggerTime | `String` (255) | 🚫 Not Null | - |
| NewCalcedPartWeight | `Boolean` | 🚫 Not Null | - |
| MaintenanceCycleTrigger | `Date` | 🚫 Not Null | - |
| UsageWarningDays | `Date` | 🚫 Not Null | - |
| ExtraSideLabel | `Real` | 🚫 Not Null | - |
| QRtype | `Picture` | 🚫 Not Null | - |
| RequiresChecking | `Real` | - | - |
| TemperatureTargetMin | `Boolean` | 🚫 Not Null | - |
| TemperatureTargetMax | `Boolean` | 🚫 Not Null | - |
| RobotHeads | `String` (255) | - | - |
| MigrationID | `Date` | - | - |
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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:43Z*
