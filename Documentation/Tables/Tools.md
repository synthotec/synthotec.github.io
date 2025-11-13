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
- **Generated:** 🕐 2025-11-13T02:34:15Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (139)
- [🔍 Indexes](#-indexes) (10)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (12)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| NextUniqueLabelID_l | `Date` | 🚫 Not Null | - |
| Approved | `Real` | 🚫 Not Null | - |
| Short Name | `String` | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| 🔑 **Tool_ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | - |
| PartNo | `String` (30) | 🚫 Not Null | - |
| ShortName | `String` (25) | 🚫 Not Null | - |
| Machine_Type | `String` | 🚫 Not Null | - |
| NumOfRows | `Date` | 🚫 Not Null | - |
| Pallet_Pic | `Picture` | 🚫 Not Null | - |
| Setup_Sheet | `Real` | 🚫 Not Null | - |
| OperatorRequired | `Real` | 🚫 Not Null | - |
| Robot_Prg_No | `String` (255) | 🚫 Not Null | - |
| Pallet_Type_m | `String` (255) | 🚫 Not Null | - |
| Tool_No | `String` (10) | ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Impressions | `Picture` | ⚠️ Required, 🚫 Not Null | - |
| Date Created | `Integer` | 🚫 Not Null, 🔒 Read-only | - |
| Box_Per_Pallet | `Picture` | 🚫 Not Null | - |
| Boxes_Per_M_Pallet | `Picture` | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |
| CycleTimeSecs | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| PartWtGrams | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| RunnerWtGrams | `Boolean` | 🚫 Not Null | - |
| Regrind_MaxPercent | `Boolean` | 🚫 Not Null | - |
| Packed_Per_Hour | `Date` | 🚫 Not Null | - |
| Mandrells_per_Pallet | `Picture` | 🚫 Not Null | - |
| Packing Box | `String` (20) | 🚫 Not Null | - |
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
| Grey box Quan | `Date` | 🚫 Not Null | - |
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
| ToolNoticeObject | `Unknown (21)` | - | - |
| ProductionHoldObject | `Unknown (21)` | - | - |

### Detailed Information

#### NextUniqueLabelID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Approved

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Short Name

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null, 👁️ Hidden

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### 🔑 Tool_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, ⚠️ Mandatory, 🚫 Never Null, 🔒 Not Modifiable

---

#### PartNo

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### ShortName

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null, 👁️ Hidden

---

#### Machine_Type

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### NumOfRows

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Pallet_Pic

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Setup_Sheet

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### OperatorRequired

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Robot_Prg_No

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Pallet_Type_m

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Tool_No

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** ✨ Unique, ⚠️ Mandatory, 🚫 Never Null

---

#### Impressions

**Properties:**

- **Type:** Picture
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Date Created

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null, 🔒 Not Enterable

---

#### Box_Per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Boxes_Per_M_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Archive

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CycleTimeSecs

**Properties:**

- **Type:** Boolean
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### PartWtGrams

**Properties:**

- **Type:** Boolean
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### RunnerWtGrams

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Regrind_MaxPercent

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Packed_Per_Hour

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Mandrells_per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Packing Box

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null, 👁️ Hidden

---

#### Dry_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### If on Concess

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### If Concess by N

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Total No Conces

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### No Concess Supp

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Concess End Dat

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### DryWeightText

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### ReasonToolOffsite_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### IsToolOffsite_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DateToolDueBack_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### TimePerPallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Picture

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Prodn Quan Min

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Production_Mandrell

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Tool_Notes

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Conditioned

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Type

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Grey box Quan

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null, 👁️ Hidden

---

#### Cages_per_Mandrell

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Concession No

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Customer Label

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Additional_text_4_label

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Nozzle

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** 🚫 Never Null

---

#### Separator

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Prodn Quan Max

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Location

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Tool Mod

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** 🚫 Never Null

---

#### Initial Cust

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### Main Tool

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Additional_text

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### UseAddressLabels_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### UseUniqueIDLabels_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### LabelChoice_s

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### UseBagLabel_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### UseExtraID_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### UseLogisticslabel_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NextUniqueIDLogistics_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Final_Customer

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Weight_kitlabel

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Kit_ProductID

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Kit_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Mandrel_OD

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### NumOfLayers

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### BagSealingMethod

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PackedInColumns

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RC_Sub_Sequence

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RC_Additional_Seq

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RC_Barcode

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### x3_sequence_packsheet

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### x4_sequence_packsheet

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### PackagingInstructionIssueDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### PackagingInstructionIssueName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### identifier_address

**Properties:**

- **Type:** String (max length: 2)
- **Constraints:** 🚫 Never Null

---

#### No_metalpallets_per_box

**Properties:**

- **Type:** Picture
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### two_boxnos

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### qty_delivered_flag

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### qty_pricechange

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### packrange_max

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### AQP

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### x2_uniqueIDlabels

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DateChanged

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### PackagingInstructionIssueLevel

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### IsHandLoaded

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### OddLayerQuantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SmallSide

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### LargeSide

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AlternatingLayerQuantA

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### AlternatingLayerQuantB

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ScalesFixedQuant

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ExtraPackInfo

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### LabelOrigin

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### QRCode

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Amber

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RunsSinceApproval

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### AmberCheckPercent

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### AmberManual

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AmberManualWhen

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### AmberManualWho

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### AmberPQITriggered

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RCText

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ForeCast2015

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ForeCast2015Update

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ProductName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PicBlob

**Properties:**

- **Type:** Unknown (18)
- **Constraints:** 🚫 Never Null

---

#### PicBlobTxt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### LogisticsPrefix

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### DataMatrix

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Regrind

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RegrindComments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### NotifyQuality

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NotifyReason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolReady

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ToolOffsite

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### StatusUpdated

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolDueDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### PlanningWheelCycle

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### PlanningWheelHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### HotHalfID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### HotHalfBooked

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AmberTriggerTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### NewCalcedPartWeight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### MaintenanceCycleTrigger

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### UsageWarningDays

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ExtraSideLabel

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### QRtype

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### RequiresChecking

**Properties:**

- **Type:** Real

---

#### TemperatureTargetMin

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TemperatureTargetMax

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### RobotHeads

**Properties:**

- **Type:** String (max length: 255)

---

#### MigrationID

**Properties:**

- **Type:** Date

---

#### ToolNoticeObject

**Properties:**

- **Type:** Unknown (21)

---

#### ProductionHoldObject

**Properties:**

- **Type:** Unknown (21)

---

## 🔍 Indexes

### Quick Reference

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

### Detailed Information

- **Field:** `MigrationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PartNo`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Archive`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ShortName`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `two_boxnos`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `HotHalfID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Tool_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `HotHalfBooked`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Tool_ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |
| `HotHalfEntity` | [HotHalfs](HotHalfs.md) | `HotHalfID` → `ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### HotHalfEntity

**Links to:** [HotHalfs](HotHalfs.md)

- **Source Field:** `HotHalfID`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `ToolID` → `Tool_ID` | Active |
| `NonConformanceSelection` | [NonConformance](NonConformance.md) | `Tool_ID` → `Tool_ID` | Active |
| `ToolLogSelection` | [ToolLog](ToolLog.md) | `Tool_ID` → `Tool_ID` | Active |
| `ApprovalsSelection` | [Approvals](Approvals.md) | `ToolID` → `Tool_ID` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `ToolID` → `Tool_ID` | Active |
| `WorkRequestsSelection` | [WorkRequests](WorkRequests.md) | `ToolID` → `Tool_ID` | Active |
| `ToolMaintenanceLogSelection` | [ToolMaintenanceLog](ToolMaintenanceLog.md) | `ToolID` → `Tool_ID` | Active |
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `ToolID` → `Tool_ID` | Active |
| `ToolDocumentSelection` | [ToolDocument](ToolDocument.md) | `ToolID` → `Tool_ID` | Active |
| `PlanningWheelSelection` | [PlanningWheel](PlanningWheel.md) | `ToolID` → `Tool_ID` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Tool ID` → `Tool_ID` | Active |
| `ToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `ToolID` → `Tool_ID` | Active |

### Detailed Information

#### WorksOrderSelection

**Links from:** [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### NonConformanceSelection

**Links from:** [NonConformance](NonConformance.md)

- **Source Table:** `NonConformance`
- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ToolLogSelection

**Links from:** [ToolLog](ToolLog.md)

- **Source Table:** `ToolLog`
- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ApprovalsSelection

**Links from:** [Approvals](Approvals.md)

- **Source Table:** `Approvals`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### WorkRequestsSelection

**Links from:** [WorkRequests](WorkRequests.md)

- **Source Table:** `WorkRequests`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ToolMaintenanceLogSelection

**Links from:** [ToolMaintenanceLog](ToolMaintenanceLog.md)

- **Source Table:** `ToolMaintenanceLog`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ToolTemperatureTargetSelection

**Links from:** [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ToolDocumentSelection

**Links from:** [ToolDocument](ToolDocument.md)

- **Source Table:** `ToolDocument`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### PlanningWheelSelection

**Links from:** [PlanningWheel](PlanningWheel.md)

- **Source Table:** `PlanningWheel`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Tool ID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ToolNoticeSelection

**Links from:** [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:15Z*
