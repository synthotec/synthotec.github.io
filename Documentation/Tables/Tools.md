---
layout : default
title : Tools
parent : Tables
---
# Tools

📊 **Overview:** 139 Fields | 10 Indexes | 14 Many-to-One Relations | 122 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 2
- **UUID:** 730DDB789A822A45A2769798BE8BF8C3
- **Primary Key:** 🔑 `Tool_ID`
- **Generated:** 🕐 2025-11-12T23:08:44Z

---

## 📑 Table of Contents

- [📋 Fields](#fields) (139)
- [🔍 Indexes](#indexes) (10)
- [🔗 Many-to-One Relations](#many-to-one-relations) (14)
- [🔗 One-to-Many Relations](#one-to-many-relations) (122)

---

## 📋 Fields

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
| `MigrationID` | - | regular | - |
| `PartNo` | - | regular | - |
| `Archive` | - | regular | - |
| `ShortName` | - | regular | - |
| `two_boxnos` | - | regular | - |
| `HotHalfID` | - | regular | - |
| `Tool_No` | - | regular | - |
| `ProductID` | - | regular | - |
| `HotHalfBooked` | - | regular | - |
| `Tool_ID` | - | regular | ✨ Yes |

### Detailed Information

- **Field:** `MigrationID`
  - **Kind:** regular
- **Field:** `PartNo`
  - **Kind:** regular
- **Field:** `Archive`
  - **Kind:** regular
- **Field:** `ShortName`
  - **Kind:** regular
- **Field:** `two_boxnos`
  - **Kind:** regular
- **Field:** `HotHalfID`
  - **Kind:** regular
- **Field:** `Tool_No`
  - **Kind:** regular
- **Field:** `ProductID`
  - **Kind:** regular
- **Field:** `HotHalfBooked`
  - **Kind:** regular
- **Field:** `Tool_ID` ✨ **(Unique)**
  - **Kind:** regular

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `Tool_ID` → `Tool_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `Tool_ID` → `Tool_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |
| `HotHalfEntity` | [HotHalfs](HotHalfs.md) | `HotHalfID` → `ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | - |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

#### HotHalfEntity

**Links to:** [HotHalfs](HotHalfs.md)

- **Source Field:** `HotHalfID`
- **Destination Field:** `ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `Customer_OrderSelection` | - | `Product_ID` → `Product_ID` | - |
| `OrderPickRequestSelection` | - | `PickRequestID` → `ID` | - |
| `Customer_OrderSelection` | - | `Material_ID` → `Unique_ID` | - |
| `WorksOrderSelection` | - | `Customer_Code` → `Customer_Code` | - |
| `WorksOrderSelection` | - | `ToolID` → `Tool_ID` | - |
| `Stock_MovementSelection` | - | `Works_Order_No_l` → `Works_Order_No` | - |
| `CofCSelection` | - | `Works_Order_No` → `Works_Order_No` | - |
| `CofCSelection` | - | `Petes No` → `Petes_No` | - |
| `Finished_StockSelection` | - | `Works_Order_No` → `Works_Order_No` | - |
| `Product_OptionSelection` | - | `Product ID` → `Product_ID` | - |
| `Product_OptionSelection` | - | `Material_ID` → `Unique_ID` | - |
| `SuppliesSelection` | - | `SupplierID_l` → `SupplierID_l` | - |
| `PurchasesSelection` | - | `SupplierID_l` → `SupplierID_l` | - |
| `PurchaseInfoSelection` | - | `OrderNo_l` → `OrderNo_l` | - |
| `GaugesSelection` | - | `Product_ID` → `Product_ID` | - |
| `GrippersSelection` | - | `Product_ID` → `Product_ID` | - |
| `RMCSelection` | - | `MaterialID_l` → `Unique_ID` | - |
| `ProductReturnSelection` | - | `ProductID_l` → `Product_ID` | - |
| `ProductReturnWorksOrderSelection` | - | `ReturnID_l` → `ReturnID_l` | - |
| `ProductReturnWorksOrderSelection` | - | `Works_Order_No_l` → `Works_Order_No` | - |
| `LanguageTagSelection` | - | `Language_ID` → `ID_l` | - |
| `BoxLabelsSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductPackagingSelection` | - | `SuppliesID` → `UniqueID_i` | - |
| `SuppliesSelection` | - | `PackagingCat` → `ID` | - |
| `Stock_MovementSelection` | - | `To_Location_l` → `StockLocationID_l` | - |
| `MaterialCheckHistorySelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `PurchaseInfoSelection` | - | `SuppliesID_i` → `UniqueID_i` | - |
| `RealTimeSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `WheelCalendarSelection` | - | `MatID` → `Unique_ID` | - |
| `ProductStockTakeSelection` | - | `WO` → `Works_Order_No` | - |
| `ScrapSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ApprovalsSelection` | - | `ToolID` → `Tool_ID` | - |
| `RTSUMSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `RealTimeSelection` | - | `DownReason` → `ID` | - |
| `WorkRequestCommentsSelection` | - | `WorkRequestID` → `ID` | - |
| `BOMSelection` | - | `MaterialID` → `Unique_ID` | - |
| `PurchaseInfoSelection` | - | `NominalCode` → `ID` | - |
| `MaterialCheckHistorySelection` | - | `MaterialID` → `Unique_ID` | - |
| `CalibrationsSelection` | - | `EquipmentID` → `ID` | - |
| `SupplierDocumentationSelection` | - | `SupplierID` → `SupplierID_l` | - |
| `ProductSelection` | - | `PalletMethodID` → `ID` | - |
| `StaffPermissionsSelection` | - | `PermissionID` → `ID` | - |
| `StaffPermissionsSelection` | - | `StaffID` → `StaffID` | - |
| `CalibrationProceduresSelection` | - | `EquipmentID` → `ID` | - |
| `CalibrationResultsSelection` | - | `CalibrationID` → `ID` | - |
| `PlanningWheelSelection` | - | `MaterialID` → `Unique_ID` | - |
| `Product_OptionSelection` | - | `Customer Code` → `Customer_Code` | - |
| `Finished_StockSelection` | - | `LocationID_l` → `StockLocationID_l` | - |
| `LinkedBoxLabelsSelection` | - | `LinkedBoxID` → `ID` | - |
| `PurchaseReceiptsSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `RMCSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `PurchaseReceiptsSelection` | - | `RMC` → `RMCNo_l` | - |
| `BoxLabelsSelection` | - | `ToolID` → `Tool_ID` | - |
| `WorksOrderSelection` | - | `ProductID_l` → `Product_ID` | - |
| `ProductSelection` | - | `EmojiID` → `ID` | - |
| `WorkRequestsSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolMaintenanceLogSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolMaintenanceLogSelection` | - | `WorkRequestID` → `ID` | - |
| `MachineMaintenanceLogSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `MachineMaintenanceRequirementsSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `DB_VariablesSelection` | - | `StaffID` → `StaffID` | - |
| `WorkRequestCommentsSelection` | - | `StaffID` → `StaffID` | - |
| `BoxLabelsSelection` | - | `PalletID` → `ID` | - |
| `FirstRealTimeSensorExceptionsSelection` | - | `FirstRealTimeID` → `ID` | - |
| `LastRealTimeSensorExceptionsSelection` | - | `LastRealTimeID` → `ID` | - |
| `RealTimeSensorExceptionsSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `RealTimeSensorExceptionsSelection` | - | `StaffID` → `StaffID` | - |
| `RealTimeMachinesSelection` | - | `DownReason` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolTemperatureTargetSelection` | - | `ZoneID` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `StaffID` → `StaffID` | - |
| `PalletSelection` | - | `LocationID` → `ID` | - |
| `LocationSelection` | - | `ParentLocationID` → `ID` | - |
| `ToolDocumentSelection` | - | `ToolID` → `Tool_ID` | - |
| `OrderPickRequestSelection` | - | `CustomerOrderID` → `Petes_No` | - |
| `ProductMaterialOptionsSelection` | - | `MaterialID` → `Unique_ID` | - |
| `MaterialStockTakeSelection` | - | `RMC` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection1` | - | `RMC1` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection2` | - | `RMC2` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection3` | - | `RMC3` → `RMCNo_l` | - |
| `PalletSelection` | - | `OrderPickRequestID` → `ID` | - |
| `BoxLabelsSelection` | - | `OrderPickRequestID` → `ID` | - |
| `PickRequestSelection` | - | `Customer` → `Customer_Code` | - |
| `BoxLabelsSelection` | - | `CofCID` → `Cert_Of_Conformance_No` | - |
| `PalletSelection` | - | `CofCID` → `Cert_Of_Conformance_No` | - |
| `CofCSelection` | - | `Advice_Note_No` → `Advice_Note_No` | - |
| `CofCSelection` | - | `LocationID_l` → `StockLocationID_l` | - |
| `CofCSelection` | - | `ProductID_l` → `Product_ID` | - |
| `PickRequestSelection` | - | `AdviceNoteID` → `ID` | - |
| `Customer_OrderSelection` | - | `Customer_Code` → `Customer_Code` | - |
| `MaterialStockSelection` | - | `MaterialID` → `Unique_ID` | - |
| `MaterialStockSelection` | - | `RMC` → `RMCNo_l` | - |
| `MaterialStockSelection` | - | `LocationID` → `ID` | - |
| `WheelCalendarSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `PrintJobSelection` | - | `PrinterID` → `ID` | - |
| `PrintJobSelection` | - | `RelatedUUID` → `UUID` | - |
| `PrintJobSelection` | - | `StaffID` → `StaffID` | - |
| `PlanningWheelSelection` | - | `ToolID` → `Tool_ID` | - |
| `BoxLabelsSelection` | - | `Stock_LocationID` → `StockLocationID_l` | - |
| `ShiftSummaryDetailSelection` | - | `ShiftSummaryID` → `ID` | - |
| `ShiftSummarySelection` | - | `StaffID` → `StaffID` | - |
| `ShiftSummaryDetailSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductSelection` | - | `DefMatID` → `Unique_ID` | - |
| `StatusUpdatedBoxLabelsSelection` | - | `StatusUpdatedStaffID` → `StaffID` | - |
| `ErrorDetailSelection` | - | `ErrorID` → `ID` | - |
| `Customer_OrderSelection` | - | `Product_OptionID` → `ID` | - |
| `CustomerSelection` | - | `ConsignmentLocationID` → `StockLocationID_l` | - |
| `UsageMat1Selection` | - | `UsageMatID` → `Unique_ID` | - |
| `UsageMat2Selection` | - | `UsageMatID2` → `Unique_ID` | - |
| `UsageMat3Selection` | - | `UsageMatID3` → `Unique_ID` | - |
| `ApprovalsSelection` | - | `Customer` → `Customer_Code` | - |
| `BOMSelection` | - | `Customer` → `Customer_Code` | - |
| `WorksOrderSelection` | - | `MaterialID` → `Unique_ID` | - |
| `Product_OptionSelection` | - | `Tool ID` → `Tool_ID` | - |
| `CustomerContactsSelection` | - | `Customer` → `Customer_Code` | - |
| `CustomerSelection` | - | `TransportInstructionFileID` → `ID` | - |
| `ProductPackagingSelection` | - | `Customer` → `Customer_Code` | - |
| `ToolNoticeSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolNoticeSelection` | - | `StaffID` → `StaffID` | - |
| `ToolNoticeWorksOrderSelection` | - | `ToolNoticeID` → `ToolID` | - |
| `ToolNoticeWorksOrderSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `DeactivatedToolNoticeSelection` | - | `DeactivatedStaffID` → `StaffID` | - |

### Detailed Information

#### Customer_OrderSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

---

#### OrderPickRequestSelection

- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`

---

#### Customer_OrderSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`

---

#### WorksOrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`

---

#### WorksOrderSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### Stock_MovementSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

---

#### CofCSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`

---

#### CofCSelection

- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`

---

#### Finished_StockSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`

---

#### Product_OptionSelection

- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`

---

#### Product_OptionSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`

---

#### SuppliesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`

---

#### PurchasesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`

---

#### PurchaseInfoSelection

- **Source Field:** `OrderNo_l`
- **This Table Field:** `OrderNo_l`

---

#### GaugesSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

---

#### GrippersSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

---

#### RMCSelection

- **Source Field:** `MaterialID_l`
- **This Table Field:** `Unique_ID`

---

#### ProductReturnSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

---

#### ProductReturnWorksOrderSelection

- **Source Field:** `ReturnID_l`
- **This Table Field:** `ReturnID_l`

---

#### ProductReturnWorksOrderSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

---

#### LanguageTagSelection

- **Source Field:** `Language_ID`
- **This Table Field:** `ID_l`

---

#### BoxLabelsSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### ProductPackagingSelection

- **Source Field:** `SuppliesID`
- **This Table Field:** `UniqueID_i`

---

#### SuppliesSelection

- **Source Field:** `PackagingCat`
- **This Table Field:** `ID`

---

#### Stock_MovementSelection

- **Source Field:** `To_Location_l`
- **This Table Field:** `StockLocationID_l`

---

#### MaterialCheckHistorySelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### PurchaseInfoSelection

- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`

---

#### RealTimeSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### WheelCalendarSelection

- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`

---

#### ProductStockTakeSelection

- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`

---

#### ScrapSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### ApprovalsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### RTSUMSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### RealTimeSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`

---

#### WorkRequestCommentsSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`

---

#### BOMSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### PurchaseInfoSelection

- **Source Field:** `NominalCode`
- **This Table Field:** `ID`

---

#### MaterialCheckHistorySelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### CalibrationsSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`

---

#### SupplierDocumentationSelection

- **Source Field:** `SupplierID`
- **This Table Field:** `SupplierID_l`

---

#### ProductSelection

- **Source Field:** `PalletMethodID`
- **This Table Field:** `ID`

---

#### StaffPermissionsSelection

- **Source Field:** `PermissionID`
- **This Table Field:** `ID`

---

#### StaffPermissionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### CalibrationProceduresSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`

---

#### CalibrationResultsSelection

- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`

---

#### PlanningWheelSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### Product_OptionSelection

- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`

---

#### Finished_StockSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`

---

#### LinkedBoxLabelsSelection

- **Source Field:** `LinkedBoxID`
- **This Table Field:** `ID`

---

#### PurchaseReceiptsSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`

---

#### RMCSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`

---

#### PurchaseReceiptsSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

---

#### BoxLabelsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### WorksOrderSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

---

#### ProductSelection

- **Source Field:** `EmojiID`
- **This Table Field:** `ID`

---

#### WorkRequestsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolMaintenanceLogSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolMaintenanceLogSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`

---

#### MachineMaintenanceLogSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

---

#### MachineMaintenanceRequirementsSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

---

#### DB_VariablesSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### WorkRequestCommentsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### BoxLabelsSelection

- **Source Field:** `PalletID`
- **This Table Field:** `ID`

---

#### FirstRealTimeSensorExceptionsSelection

- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`

---

#### LastRealTimeSensorExceptionsSelection

- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`

---

#### RealTimeSensorExceptionsSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### RealTimeSensorExceptionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### RealTimeMachinesSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`

---

#### ToolTemperatureTargetSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolTemperatureTargetSelection

- **Source Field:** `ZoneID`
- **This Table Field:** `ID`

---

#### ToolTemperatureTargetSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### PalletSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`

---

#### LocationSelection

- **Source Field:** `ParentLocationID`
- **This Table Field:** `ID`

---

#### ToolDocumentSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### OrderPickRequestSelection

- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`

---

#### ProductMaterialOptionsSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### MaterialStockTakeSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

---

#### MaterialCheckHistorySelection1

- **Source Field:** `RMC1`
- **This Table Field:** `RMCNo_l`

---

#### MaterialCheckHistorySelection2

- **Source Field:** `RMC2`
- **This Table Field:** `RMCNo_l`

---

#### MaterialCheckHistorySelection3

- **Source Field:** `RMC3`
- **This Table Field:** `RMCNo_l`

---

#### PalletSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`

---

#### BoxLabelsSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`

---

#### PickRequestSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### BoxLabelsSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`

---

#### PalletSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`

---

#### CofCSelection

- **Source Field:** `Advice_Note_No`
- **This Table Field:** `Advice_Note_No`

---

#### CofCSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`

---

#### CofCSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

---

#### PickRequestSelection

- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`

---

#### Customer_OrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`

---

#### MaterialStockSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### MaterialStockSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

---

#### MaterialStockSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`

---

#### WheelCalendarSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### PrintJobSelection

- **Source Field:** `PrinterID`
- **This Table Field:** `ID`

---

#### PrintJobSelection

- **Source Field:** `RelatedUUID`
- **This Table Field:** `UUID`

---

#### PrintJobSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### PlanningWheelSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### BoxLabelsSelection

- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`

---

#### ShiftSummaryDetailSelection

- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`

---

#### ShiftSummarySelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### ShiftSummaryDetailSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### ProductSelection

- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`

---

#### StatusUpdatedBoxLabelsSelection

- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`

---

#### ErrorDetailSelection

- **Source Field:** `ErrorID`
- **This Table Field:** `ID`

---

#### Customer_OrderSelection

- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`

---

#### CustomerSelection

- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`

---

#### UsageMat1Selection

- **Source Field:** `UsageMatID`
- **This Table Field:** `Unique_ID`

---

#### UsageMat2Selection

- **Source Field:** `UsageMatID2`
- **This Table Field:** `Unique_ID`

---

#### UsageMat3Selection

- **Source Field:** `UsageMatID3`
- **This Table Field:** `Unique_ID`

---

#### ApprovalsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### BOMSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### WorksOrderSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### Product_OptionSelection

- **Source Field:** `Tool ID`
- **This Table Field:** `Tool_ID`

---

#### CustomerContactsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### CustomerSelection

- **Source Field:** `TransportInstructionFileID`
- **This Table Field:** `ID`

---

#### ProductPackagingSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### ToolNoticeSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolNoticeSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### ToolNoticeWorksOrderSelection

- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`

---

#### ToolNoticeWorksOrderSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### DeactivatedToolNoticeSelection

- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:08:44Z*
