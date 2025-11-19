---
layout : default
title : Product
parent : Tables
---
# Product

📊 **Overview:** 105 Fields | 7 Indexes | 3 Many-to-One Relations | 18 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 10
- **UUID:** C860B832DC3A2742AC90F8A95BC2F157
- **Primary Key:** 🔑 `Product_ID`
- **Generated:** 🕐 2025-11-13T23:17:50Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (105)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (18)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (40)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Product_ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Our Part No | `String` (50) | ⚠️ Required, 🚫 Not Null | - |
| Cust Part No | `String` (50) | ⚠️ Required, 🚫 Not Null | - |
| Issue No | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Issue Date | `Integer` | 🚫 Not Null | - |
| Part Name | `String` (50) | ⚠️ Required, 🚫 Not Null | - |
| Short Name | `String` (25) | ⚠️ Required, 🚫 Not Null | - |
| Conditioned | `Real` | 🚫 Not Null | - |
| QuotedCycle | `Boolean` | 🚫 Not Null, ��� Not Modifiable | - |
| DefMatID | `Date` | 🚫 Not Null | - |
| Price Quan | `Picture` | 🚫 Not Null | - |
| NoInBox | `Date` | 🚫 Not Null | - |
| Min Order Quan | `Date` | 🚫 Not Null | - |
| NumOfSquirts | `Date` | 🚫 Not Null | - |
| Drawing No | `String` (25) | 🚫 Not Null | - |
| Regrnd allwd pc | `Picture` | 🚫 Not Null | - |
| Odette_PO | `String` (255) | 🚫 Not Null | - |
| Packed_Per_Hour | `Date` | 🚫 Not Null | - |
| Programme_No | `String` (3) | 🚫 Not Null | - |
| Tolerance_Low | `Boolean` | 🚫 Not Null | - |
| Tolerance_High | `Boolean` | 🚫 Not Null | - |
| TimePerPallet | `Picture` | 🚫 Not Null | - |
| MBType | `String` (255) | 🚫 Not Null | - |
| MBAmount | `Picture` | 🚫 Not Null | - |
| EmojiID | `Date` | - | - |
| Archive | `Real` | 🚫 Not Null | - |
| Inspection Issue | `Picture` | 🚫 Not Null | - |
| Inspection IssueDate | `Integer` | 🚫 Not Null | - |
| Inspection IssuedBy | `String` (20) | 🚫 Not Null | - |
| Inspect Method1 | `String` | 🚫 Not Null | - |
| Inspect Method2 | `String` | 🚫 Not Null | - |
| Inspect Method3 | `String` | 🚫 Not Null | - |
| Inspect Method4 | `String` | 🚫 Not Null | - |
| Inspect Method5 | `String` | 🚫 Not Null | - |
| Patrol Inspect1 | `String` | 🚫 Not Null | - |
| Patrol Inspect2 | `String` | 🚫 Not Null | - |
| Patrol Inspect3 | `String` | 🚫 Not Null | - |
| Patrol Inspect4 | `String` | 🚫 Not Null | - |
| Conversion_Figure | `String` (50) | 🚫 Not Null | - |
| Quality_FormNo | `Picture` | 🚫 Not Null | - |
| Quality_IssueDate | `Integer` | 🚫 Not Null | - |
| Quality_Issuedby | `String` (10) | 🚫 Not Null | - |
| Quality_ReferenceNo | `String` (10) | 🚫 Not Null | - |
| Initial_Customer | `String` (3) | 🚫 Not Null | - |
| OperatorRequired | `Real` | 🚫 Not Null | - |
| Inspect_Freq_qty | `Picture` | 🚫 Not Null | - |
| Inspect_freq_cycle | `Picture` | 🚫 Not Null | - |
| Inspect_freq_period | `String` (9) | 🚫 Not Null | - |
| Extra_Text | `String` (40) | 🚫 Not Null | - |
| Box_Per_Pallet | `Picture` | 🚫 Not Null | - |
| Top_Up_No | `Picture` | 🚫 Not Null | - |
| Cond_Cycl_Lght | `Picture` | 🚫 Not Null | - |
| Part_No_Colour | `Picture` | 🚫 Not Null | - |
| Part_Colour | `String` | 🚫 Not Null | - |
| Reason_4_Issue_Change | `String` (20) | 🚫 Not Null | - |
| Danzas_ID | `Picture` | 🚫 Not Null | - |
| Cages_per_Mandrell | `Picture` | 🚫 Not Null | - |
| Boxes_per_M_Pallet | `Picture` | 🚫 Not Null | - |
| Pallet_Type_m | `String` (5) | 🚫 Not Null | - |
| OurMinimum | `Date` | 🚫 Not Null | - |
| Robot_Prg_No | `String` (255) | 🚫 Not Null | - |
| Pallet_Pic | `Picture` | 🚫 Not Null | - |
| Production_Mandrell | `String` (30) | 🚫 Not Null | - |
| Mandrells_per_Pallet | `Picture` | 🚫 Not Null | - |
| Mandrel_OD | `Boolean` | 🚫 Not Null | - |
| OurBatchSize | `Date` | 🚫 Not Null | - |
| PrimaryRoute | `Picture` | 🚫 Not Null | - |
| Setup_Sheet | `Real` | 🚫 Not Null | - |
| Danzas_ID1 | `Picture` | 🚫 Not Null | - |
| Danzas_ID2 | `Picture` | 🚫 Not Null | - |
| ControlPlanLink1_txt | `String` | 🚫 Not Null | - |
| ControlPlanLink2_txt | `String` | 🚫 Not Null | - |
| Water_Squirt_prog_number | `Boolean` | 🚫 Not Null | - |
| RunsPerForecast | `Date` | 🚫 Not Null | - |
| StockTowardsForecast | `Undefined` | 🚫 Not Null | - |
| ForecastQty | `Undefined` | 🚫 Not Null | - |
| ForecastOutstanding | `Undefined` | 🚫 Not Null | - |
| CoveredByWheel | `Undefined` | 🚫 Not Null | - |
| MagicNumber | `Boolean` | 🚫 Not Null | - |
| Field_80 | `String` (255) | 🚫 Not Null | - |
| RoutedElsewhere | `Undefined` | 🚫 Not Null | - |
| ConsignmentOrder | `Real` | 🚫 Not Null | - |
| HoursOverride | `Boolean` | 🚫 Not Null | - |
| Inspect_Freq_MIN | `Picture` | 🚫 Not Null | - |
| PlannedRoute | `Picture` | 🚫 Not Null | - |
| SecondCode | `String` (255) | 🚫 Not Null | - |
| UsedSinceBill | `Date` | 🚫 Not Null | - |
| WareHouseMethod | `String` (255) | 🚫 Not Null | - |
| PrioritizeStandardOrders | `Real` | 🚫 Not Null | - |
| TotalPackTime | `Boolean` | 🚫 Not Null | - |
| TotalPackInstances | `Date` | 🚫 Not Null | - |
| TotalPackString | `String` (255) | 🚫 Not Null | - |
| SecondLocation | `String` (255) | 🚫 Not Null | - |
| BottomPackTimeTarget | `Boolean` | 🚫 Not Null | - |
| BottomPackTimeOverride | `Long Integer` | 🚫 Not Null | - |
| PalletMethodID | `Date` | 🚫 Not Null | - |
| ClosedLoopPercent | `Boolean` | 🚫 Not Null | - |
| ForecastOutstandingCurrentYear | `Date` | 🚫 Not Null | - |
| AverageRunLength | `Boolean` | 🚫 Not Null | - |
| SubContainerQty | `Date` | 🚫 Not Null | - |
| SubContainerName | `String` (255) | 🚫 Not Null | - |
| PackingInstructionsFileBlob | `Unknown (18)` | - | - |
| PackingInstructionsFileName | `String` (255) | - | - |
| MigrationID | `Date` | 🚫 Not Null | - |
| LastMigration | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `MigrationID` | Keywords | regular | - |
| `PrimaryRoute` | Cluster | regular | - |
| `Product_ID` | Keywords | regular | ✨ Yes |
| `DefMatID` | Keywords | regular | - |
| `Cust Part No` | Keywords | regular | - |
| `EmojiID` | Keywords | regular | - |
| `Our Part No` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `PalletMethodsEntity` | [PalletMethods](PalletMethods.md) | `PalletMethodID` → `ID` | Active | - |
| `EmojisEntity` | [Emojis](Emojis.md) | `EmojiID` → `ID` | Active | - |
| `MaterialEntity` | [Material](Material.md) | `DefMatID` → `Unique_ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ToolsSelection` | [Tools](Tools.md) | `ProductID` → `Product_ID` | Active | - |
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Product_ID` → `Product_ID` | Active | - |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Product ID` → `Product_ID` | Active | - |
| `GaugesSelection` | [Gauges](Gauges.md) | `Product_ID` → `Product_ID` | Active | - |
| `GrippersSelection` | [Grippers](Grippers.md) | `Product_ID` → `Product_ID` | Active | - |
| `ProductReturnSelection` | [ProductReturn](ProductReturn.md) | `ProductID_l` → `Product_ID` | Active | - |
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `ProductID` → `Product_ID` | Active | - |
| `ProductStocktakeSelection` | [ProductStockTake](ProductStockTake.md) | `ProductID` → `Product_ID` | Active | - |
| `ConsignmentEntrySelection` | [ConsignmentEntry](ConsignmentEntry.md) | `ProductID` → `Product_ID` | Active | - |
| `BOMSelection` | [BOM](BOM.md) | `ProductID` → `Product_ID` | Active | - |
| `PalletSelection` | [Pallet](Pallet.md) | `ProductID` → `Product_ID` | Active | - |
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `ProductID_l` → `Product_ID` | Active | - |
| `PackingInstructionFilesSelection` | [PackingInstructionFiles](PackingInstructionFiles.md) | `ProductID` → `Product_ID` | Active | - |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `ProductID` → `Product_ID` | Active | - |
| `ProductMaterialOptionsSelection` | [ProductMaterialOptions](ProductMaterialOptions.md) | `ProductID` → `Product_ID` | Active | - |
| `CofCSelection` | [CofC](CofC.md) | `ProductID_l` → `Product_ID` | Active | - |
| `ForecastSelection` | [Forecast](Forecast.md) | `ProductID` → `Product_ID` | Active | - |
| `QualitySystemProceduresSelection` | [QualitySystemProcedures](QualitySystemProcedures.md) | `ProductID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Product](../Classes/Product.md) - ORDA DataClass class for Product table
- [ProductEntity](../Classes/ProductEntity.md) - ORDA Entity class for Product table

### 📄 Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [%2AStockControl](../Forms/%2AStockControl.md) - Data source for %2AStockControl form
- [%2Atest1](../Forms/%2Atest1.md) - Data source for %2Atest1 form
- [%2AToolEditor](../Forms/%2AToolEditor.md) - Data source for %2AToolEditor form
- [BOM](../Forms/BOM.md) - Data source for BOM form
- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [BOM_Output](../Forms/BOM_Output.md) - Data source for BOM_Output form
- [BOM_Packaging](../Forms/BOM_Packaging.md) - Data source for BOM_Packaging form
- [CapacityPlanning](../Forms/CapacityPlanning.md) - Data source for CapacityPlanning form
- [ChangeMaterial](../Forms/ChangeMaterial.md) - Data source for ChangeMaterial form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [EDIgenerator](../Forms/EDIgenerator.md) - Data source for EDIgenerator form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [ForecastImporter](../Forms/ForecastImporter.md) - Data source for ForecastImporter form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [NSKPalletIDs](../Forms/NSKPalletIDs.md) - Data source for NSKPalletIDs form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [PackingLabour](../Forms/PackingLabour.md) - Data source for PackingLabour form
- [PalletTransfer](../Forms/PalletTransfer.md) - Data source for PalletTransfer form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [ProductStockTake](../Forms/ProductStockTake.md) - Data source for ProductStockTake form
- [QualitySystemResults](../Forms/QualitySystemResults.md) - Data source for QualitySystemResults form
- [QualitySystemTolerances](../Forms/QualitySystemTolerances.md) - Data source for QualitySystemTolerances form
- [QuarantineManager](../Forms/QuarantineManager.md) - Data source for QuarantineManager form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form
- [StockAtLocation](../Forms/StockAtLocation.md) - Data source for StockAtLocation form
- [ToolDisplay4](../Forms/ToolDisplay4.md) - Data source for ToolDisplay4 form
- [ToolStandardsReview](../Forms/ToolStandardsReview.md) - Data source for ToolStandardsReview form
- [WarehouseOptions](../Forms/WarehouseOptions.md) - Data source for WarehouseOptions form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:50Z*
