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
- **Generated:** 🕐 2025-11-13T23:17:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (85)
- [🔍 Indexes](#-indexes) (18)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (14)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

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

## 🔍 Indexes

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

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | Active | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `Stock_MovementSelection` | [Stock_Movement](Stock_Movement.md) | `Works_Order_No_l` → `Works_Order_No` | Active | - |
| `CofCSelection` | [CofC](CofC.md) | `Works_Order_No` → `Works_Order_No` | Active | - |
| `Finished_StockSelection` | [Finished_Stock](Finished_Stock.md) | `Works_Order_No` → `Works_Order_No` | Active | - |
| `ProductReturnWorksOrderSelection` | [ProductReturnWorksOrder](ProductReturnWorksOrder.md) | `Works_Order_No_l` → `Works_Order_No` | Active | - |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `MaterialCheckHistorySelection` | [MaterialCheckHistory](MaterialCheckHistory.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `RealTimeSelection` | [RealTime](RealTime.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `ProductStockTakeSelection` | [ProductStockTake](ProductStockTake.md) | `WO` → `Works_Order_No` | Active | - |
| `ScrapSelection` | [Scrap](Scrap.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `RTSUMSelection` | [RTSUM](RTSUM.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `RealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `ShiftSummaryDetailSelection` | [ShiftSummaryDetail](ShiftSummaryDetail.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `ToolNoticeWorksOrderSelection` | [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [WorksOrder](../Classes/WorksOrder.md) - ORDA DataClass class for WorksOrder table
- [WorksOrderEntity](../Classes/WorksOrderEntity.md) - ORDA Entity class for WorksOrder table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:45Z*
