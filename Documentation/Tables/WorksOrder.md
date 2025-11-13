---
layout : default
title : WorksOrder
parent : Tables
---
# WorksOrder

📊 **Overview:** 85 Fields | 18 Indexes | 4 Many-to-One Relations | 14 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 4
- **UUID:** 305DC4E1E3339443B76C086981BBCB7C
- **Primary Key:** 🔑 `Works_Order_No`
- **Generated:** 🕐 2025-11-13T02:34:17Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (85)
- [🔍 Indexes](#-indexes) (18)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (14)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Works_Order_No** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | - |
| Part_No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Customer_Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Production_Target | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Parts_Packed | `Date` | 🚫 Not Null | - |
| Raised_Job_Card | `Real` | 🚫 Not Null | - |
| Machine_Completed | `Real` | 🚫 Not Null | - |
| RouteCards | `Real` | 🚫 Not Null | - |
| Notes | `String` | 🚫 Not Null | - |
| Labels | `Real` | 🚫 Not Null | - |
| SequencedNo | `Undefined` | 🚫 Not Null | - |
| Quantity_Manufactured | `Date` | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Tool_No | `String` (5) | 🚫 Not Null | - |
| No_In_Stock | `Date` | 🚫 Not Null | - |
| MaterialName | `String` (80) | ⚠️ Required, 🚫 Not Null | - |
| MaterialID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Issue_No | `String` (5) | 🚫 Not Null | - |
| ProductID_l | `Date` | 🚫 Not Null | - |
| Packing_Completed | `Real` | 🚫 Not Null | - |
| Calculated_Scrap | `Date` | 🚫 Not Null | - |
| Label_Text | `String` (80) | 🚫 Not Null | - |
| RMC_Nos | `String` (61) | 🚫 Not Null | - |
| Machine_No | `Picture` | 🚫 Not Null | - |
| Completed_Date | `Integer` | 🚫 Not Null | - |
| Packing_Box_No | `Date` | 🚫 Not Null | - |
| Machine_Started | `Real` | 🚫 Not Null | - |
| WorkInProgress | `Date` | 🚫 Not Null | - |
| Current_Production_Quantity | `Date` | 🚫 Not Null | - |
| UpdatePartsMadeDate | `Integer` | 🚫 Not Null | - |
| Is_a_Trial | `Real` | 🚫 Not Null | - |
| Parts_Delivered | `Date` | 🚫 Not Null | - |
| Date_Created | `Integer` | 🚫 Not Null | - |
| Quarantine_Finished_Stock | `Date` | 🚫 Not Null | - |
| DrawingNo | `String` (25) | 🚫 Not Null | - |
| Start_Date | `Integer` | 🚫 Not Null | - |
| PackingSheetPrinted | `Real` | 🚫 Not Null | - |
| Cycle_Time | `Boolean` | 🚫 Not Null | - |
| Entered_Parts_Scrap | `Date` | 🚫 Not Null | - |
| Fin_Initals | `String` (30) | 🚫 Not Null | - |
| Part_Weight | `Boolean` | 🚫 Not Null | - |
| Runner_Weight | `Boolean` | 🚫 Not Null | - |
| Weight_Initals | `String` (30) | 🚫 Not Null | - |
| Dry_Weight | `Boolean` | 🚫 Not Null | - |
| Fin_Packed_Date | `Integer` | 🚫 Not Null | - |
| Production_Chart_Status | `Real` | 🚫 Not Null | - |
| Production_Chart_DateSent | `Integer` | 🚫 Not Null | - |
| Quarantined_b | `Real` | 🚫 Not Null | - |
| Quarantine_UnpackedWIP_Stock | `Date` | 🚫 Not Null | - |
| ReturnsScrap_l | `Date` | 🚫 Not Null | - |
| Quarantine_Returned_Stock_l | `Date` | 🚫 Not Null | - |
| Barcodenum_Part | `String` | 🚫 Not Null | - |
| Barcodepicture_part | `String` | 🚫 Not Null | - |
| Barcodenum_quantity | `String` | 🚫 Not Null | - |
| Barcodepicture_quantity | `String` | 🚫 Not Null | - |
| Barcodenum_supplierid | `String` | 🚫 Not Null | - |
| Barcodepicture_supplierid | `String` | 🚫 Not Null | - |
| Barcodenum_labelid | `String` | 🚫 Not Null | - |
| Barcodepicture_labelid | `String` | 🚫 Not Null | - |
| Barcodepicture_workorder | `String` | 🚫 Not Null | - |
| Barcodenum_worksorder | `String` | 🚫 Not Null | - |
| Cycle_Flag | `Real` | 🚫 Not Null | - |
| AmberQuarantine | `Real` | 🚫 Not Null | - |
| StartTime | `Long Integer` | 🚫 Not Null | - |
| FinishTime | `Long Integer` | 🚫 Not Null | - |
| rFtime | `Boolean` | 🚫 Not Null | - |
| rStime | `Boolean` | 🚫 Not Null | - |
| SetDate | `Integer` | 🚫 Not Null | - |
| FirstOffCompleted | `Real` | 🚫 Not Null | - |
| FirstOffComments | `String` | 🚫 Not Null | - |
| Impressions | `Picture` | 🚫 Not Null | - |
| NewSystem | `Real` | 🚫 Not Null | - |
| AutomaticStock | `Real` | 🚫 Not Null | - |
| Robot | `Real` | 🚫 Not Null | - |
| QuarantineReason | `String` (255) | 🚫 Not Null | - |
| FirstOffWeightsChecked | `Real` | 🚫 Not Null | - |
| PlannedMaterialID | `Date` | 🚫 Not Null | - |
| Regrind | `Real` | 🚫 Not Null | - |
| MaterialCheckedBy | `String` (255) | 🚫 Not Null | - |
| MaterialCheckComment | `String` (255) | 🚫 Not Null | - |
| OEEgenerated | `Real` | 🚫 Not Null | - |
| LastProcessedRealTimeID | `Date` | - | - |
| FixedDate | `Integer` | - | - |
| MigrationID | `Date` | - | - |
| LastMigration | `String` (255) | - | - |

### Detailed Information

#### 🔑 Works_Order_No

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, ⚠️ Mandatory, 🚫 Never Null

---

#### Part_No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Production_Target

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Parts_Packed

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Raised_Job_Card

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Machine_Completed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RouteCards

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Notes

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Labels

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### SequencedNo

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### Quantity_Manufactured

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Tool_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### No_In_Stock

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MaterialName

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Issue_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Packing_Completed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Calculated_Scrap

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Label_Text

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### RMC_Nos

**Properties:**

- **Type:** String (max length: 61)
- **Constraints:** 🚫 Never Null

---

#### Machine_No

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Completed_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Packing_Box_No

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Machine_Started

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### WorkInProgress

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Current_Production_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### UpdatePartsMadeDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Is_a_Trial

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Parts_Delivered

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Date_Created

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Quarantine_Finished_Stock

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DrawingNo

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Start_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### PackingSheetPrinted

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Cycle_Time

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Entered_Parts_Scrap

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Fin_Initals

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Part_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Runner_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Weight_Initals

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Dry_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Fin_Packed_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Production_Chart_Status

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Production_Chart_DateSent

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Quarantined_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Quarantine_UnpackedWIP_Stock

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ReturnsScrap_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Quarantine_Returned_Stock_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Barcodenum_Part

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodepicture_part

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodenum_quantity

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodepicture_quantity

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodenum_supplierid

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodepicture_supplierid

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodenum_labelid

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodepicture_labelid

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodepicture_workorder

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Barcodenum_worksorder

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Cycle_Flag

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AmberQuarantine

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### StartTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### FinishTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### rFtime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### rStime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### SetDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### FirstOffCompleted

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### FirstOffComments

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Impressions

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NewSystem

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AutomaticStock

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Robot

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### QuarantineReason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FirstOffWeightsChecked

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### PlannedMaterialID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Regrind

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### MaterialCheckedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MaterialCheckComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### OEEgenerated

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### LastProcessedRealTimeID

**Properties:**

- **Type:** Date

---

#### FixedDate

**Properties:**

- **Type:** Integer

---

#### MigrationID

**Properties:**

- **Type:** Date

---

#### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `OEEgenerated` | Keywords | regular | - |
| `Raised_Job_Card` | Keywords | regular | - |
| `Machine_Started` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |
| `No_In_Stock` | Keywords | regular | - |
| `NewSystem` | Cluster | regular | - |
| `Machine_No` | Keywords | regular | - |
| `Part_No` | Keywords | regular | - |
| `Customer_Code` | Keywords | regular | - |
| `Works_Order_No` | Keywords | regular | ✨ Yes |
| `ToolID` | Keywords | regular | - |
| `Issue_No` | Keywords | regular | - |
| `Machine_Completed` | Keywords | regular | - |
| `ProductID_l` | Keywords | regular | - |
| `Packing_Completed` | Keywords | regular | - |
| `Robot` | Cluster | regular | - |
| `MigrationID` | Keywords | regular | - |
| `AutomaticStock` | Cluster | regular | - |

### Detailed Information

- **Field:** `OEEgenerated`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Raised_Job_Card`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine_Started`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MaterialID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `No_In_Stock`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `NewSystem`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `Machine_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Part_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer_Code`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Works_Order_No` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Issue_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine_Completed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Packing_Completed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Robot`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `MigrationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `AutomaticStock`
  - **Kind:** regular
  - **Type:** Cluster

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | Active |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active |

### Detailed Information

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `Stock_MovementSelection` | [Stock_Movement](Stock_Movement.md) | `Works_Order_No_l` → `Works_Order_No` | Active |
| `CofCSelection` | [CofC](CofC.md) | `Works_Order_No` → `Works_Order_No` | Active |
| `Finished_StockSelection` | [Finished_Stock](Finished_Stock.md) | `Works_Order_No` → `Works_Order_No` | Active |
| `ProductReturnWorksOrderSelection` | [ProductReturnWorksOrder](ProductReturnWorksOrder.md) | `Works_Order_No_l` → `Works_Order_No` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `WorksOrder` → `Works_Order_No` | Active |
| `MaterialCheckHistorySelection` | [MaterialCheckHistory](MaterialCheckHistory.md) | `WorksOrder` → `Works_Order_No` | Active |
| `RealTimeSelection` | [RealTime](RealTime.md) | `WorksOrder` → `Works_Order_No` | Active |
| `ProductStockTakeSelection` | [ProductStockTake](ProductStockTake.md) | `WO` → `Works_Order_No` | Active |
| `ScrapSelection` | [Scrap](Scrap.md) | `WorksOrder` → `Works_Order_No` | Active |
| `RTSUMSelection` | [RTSUM](RTSUM.md) | `WorksOrder` → `Works_Order_No` | Active |
| `RealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `WorksOrder` → `Works_Order_No` | Active |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `WorksOrder` → `Works_Order_No` | Active |
| `ShiftSummaryDetailSelection` | [ShiftSummaryDetail](ShiftSummaryDetail.md) | `WorksOrder` → `Works_Order_No` | Active |
| `ToolNoticeWorksOrderSelection` | [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |

### Detailed Information

#### Stock_MovementSelection

**Links from:** [Stock_Movement](Stock_Movement.md)

- **Source Table:** `Stock_Movement`
- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### CofCSelection

**Links from:** [CofC](CofC.md)

- **Source Table:** `CofC`
- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### Finished_StockSelection

**Links from:** [Finished_Stock](Finished_Stock.md)

- **Source Table:** `Finished_Stock`
- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ProductReturnWorksOrderSelection

**Links from:** [ProductReturnWorksOrder](ProductReturnWorksOrder.md)

- **Source Table:** `ProductReturnWorksOrder`
- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### MaterialCheckHistorySelection

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### RealTimeSelection

**Links from:** [RealTime](RealTime.md)

- **Source Table:** `RealTime`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ProductStockTakeSelection

**Links from:** [ProductStockTake](ProductStockTake.md)

- **Source Table:** `ProductStockTake`
- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ScrapSelection

**Links from:** [Scrap](Scrap.md)

- **Source Table:** `Scrap`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### RTSUMSelection

**Links from:** [RTSUM](RTSUM.md)

- **Source Table:** `RTSUM`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### RealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### WheelCalendarSelection

**Links from:** [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ShiftSummaryDetailSelection

**Links from:** [ShiftSummaryDetail](ShiftSummaryDetail.md)

- **Source Table:** `ShiftSummaryDetail`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ToolNoticeWorksOrderSelection

**Links from:** [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md)

- **Source Table:** `ToolNoticeWorksOrder`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:17Z*
