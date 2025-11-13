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
- **Generated:** 🕐 2025-11-13T02:34:23Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (105)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (18)

---

## 📋 Fields

### Quick Reference

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
| QuotedCycle | `Boolean` | 🚫 Not Null | - |
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

### Detailed Information

#### 🔑 Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Our Part No

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Cust Part No

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Issue No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Issue Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Part Name

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Short Name

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Conditioned

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### QuotedCycle

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null, 🔒 Not Modifiable

---

#### DefMatID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Price Quan

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NoInBox

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Min Order Quan

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### NumOfSquirts

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Drawing No

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Regrnd allwd pc

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Odette_PO

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Packed_Per_Hour

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Programme_No

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### Tolerance_Low

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Tolerance_High

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TimePerPallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### MBType

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MBAmount

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### EmojiID

**Properties:**

- **Type:** Date

---

#### Archive

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Inspection Issue

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Inspection IssueDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Inspection IssuedBy

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Inspect Method1

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Inspect Method2

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Inspect Method3

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Inspect Method4

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Inspect Method5

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Patrol Inspect1

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Patrol Inspect2

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Patrol Inspect3

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Patrol Inspect4

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Conversion_Figure

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** 🚫 Never Null

---

#### Quality_FormNo

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Quality_IssueDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Quality_Issuedby

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** 🚫 Never Null

---

#### Quality_ReferenceNo

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** 🚫 Never Null

---

#### Initial_Customer

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### OperatorRequired

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Inspect_Freq_qty

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Inspect_freq_cycle

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Inspect_freq_period

**Properties:**

- **Type:** String (max length: 9)
- **Constraints:** 🚫 Never Null

---

#### Extra_Text

**Properties:**

- **Type:** String (max length: 40)
- **Constraints:** 🚫 Never Null

---

#### Box_Per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Top_Up_No

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Cond_Cycl_Lght

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Part_No_Colour

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Part_Colour

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Reason_4_Issue_Change

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Danzas_ID

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Cages_per_Mandrell

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Boxes_per_M_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Pallet_Type_m

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### OurMinimum

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Robot_Prg_No

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Pallet_Pic

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Production_Mandrell

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Mandrells_per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Mandrel_OD

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### OurBatchSize

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PrimaryRoute

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Setup_Sheet

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Danzas_ID1

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Danzas_ID2

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### ControlPlanLink1_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### ControlPlanLink2_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Water_Squirt_prog_number

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### RunsPerForecast

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### StockTowardsForecast

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### ForecastQty

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### ForecastOutstanding

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### CoveredByWheel

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### MagicNumber

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Field_80

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### RoutedElsewhere

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### ConsignmentOrder

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### HoursOverride

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Inspect_Freq_MIN

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### PlannedRoute

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### SecondCode

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### UsedSinceBill

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WareHouseMethod

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PrioritizeStandardOrders

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### TotalPackTime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TotalPackInstances

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### TotalPackString

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### SecondLocation

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### BottomPackTimeTarget

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### BottomPackTimeOverride

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### PalletMethodID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ClosedLoopPercent

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### ForecastOutstandingCurrentYear

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### AverageRunLength

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### SubContainerQty

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SubContainerName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PackingInstructionsFileBlob

**Properties:**

- **Type:** Unknown (18)

---

#### PackingInstructionsFileName

**Properties:**

- **Type:** String (max length: 255)

---

#### MigrationID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `MigrationID` | Keywords | regular | - |
| `PrimaryRoute` | Cluster | regular | - |
| `Product_ID` | Keywords | regular | ✨ Yes |
| `DefMatID` | Keywords | regular | - |
| `Cust Part No` | Keywords | regular | - |
| `EmojiID` | Keywords | regular | - |
| `Our Part No` | Keywords | regular | - |

### Detailed Information

- **Field:** `MigrationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PrimaryRoute`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `Product_ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `DefMatID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Cust Part No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `EmojiID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Our Part No`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `PalletMethodsEntity` | [PalletMethods](PalletMethods.md) | `PalletMethodID` → `ID` | Active |
| `EmojisEntity` | [Emojis](Emojis.md) | `EmojiID` → `ID` | Active |
| `MaterialEntity` | [Material](Material.md) | `DefMatID` → `Unique_ID` | Active |

### Detailed Information

#### PalletMethodsEntity

**Links to:** [PalletMethods](PalletMethods.md)

- **Source Field:** `PalletMethodID`
- **Destination Field:** `ID`
- **State:** Active

---

#### EmojisEntity

**Links to:** [Emojis](Emojis.md)

- **Source Field:** `EmojiID`
- **Destination Field:** `ID`
- **State:** Active

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `DefMatID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ToolsSelection` | [Tools](Tools.md) | `ProductID` → `Product_ID` | Active |
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Product_ID` → `Product_ID` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Product ID` → `Product_ID` | Active |
| `GaugesSelection` | [Gauges](Gauges.md) | `Product_ID` → `Product_ID` | Active |
| `GrippersSelection` | [Grippers](Grippers.md) | `Product_ID` → `Product_ID` | Active |
| `ProductReturnSelection` | [ProductReturn](ProductReturn.md) | `ProductID_l` → `Product_ID` | Active |
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `ProductID` → `Product_ID` | Active |
| `ProductStocktakeSelection` | [ProductStockTake](ProductStockTake.md) | `ProductID` → `Product_ID` | Active |
| `ConsignmentEntrySelection` | [ConsignmentEntry](ConsignmentEntry.md) | `ProductID` → `Product_ID` | Active |
| `BOMSelection` | [BOM](BOM.md) | `ProductID` → `Product_ID` | Active |
| `PalletSelection` | [Pallet](Pallet.md) | `ProductID` → `Product_ID` | Active |
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `ProductID_l` → `Product_ID` | Active |
| `PackingInstructionFilesSelection` | [PackingInstructionFiles](PackingInstructionFiles.md) | `ProductID` → `Product_ID` | Active |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `ProductID` → `Product_ID` | Active |
| `ProductMaterialOptionsSelection` | [ProductMaterialOptions](ProductMaterialOptions.md) | `ProductID` → `Product_ID` | Active |
| `CofCSelection` | [CofC](CofC.md) | `ProductID_l` → `Product_ID` | Active |
| `ForecastSelection` | [Forecast](Forecast.md) | `ProductID` → `Product_ID` | Active |
| `QualitySystemProceduresSelection` | [QualitySystemProcedures](QualitySystemProcedures.md) | `ProductID` → `Product_ID` | Active |

### Detailed Information

#### ToolsSelection

**Links from:** [Tools](Tools.md)

- **Source Table:** `Tools`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### Customer_OrderSelection

**Links from:** [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### GaugesSelection

**Links from:** [Gauges](Gauges.md)

- **Source Table:** `Gauges`
- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### GrippersSelection

**Links from:** [Grippers](Grippers.md)

- **Source Table:** `Grippers`
- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### ProductReturnSelection

**Links from:** [ProductReturn](ProductReturn.md)

- **Source Table:** `ProductReturn`
- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### ProductPackagingSelection

**Links from:** [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### ProductStocktakeSelection

**Links from:** [ProductStockTake](ProductStockTake.md)

- **Source Table:** `ProductStockTake`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### ConsignmentEntrySelection

**Links from:** [ConsignmentEntry](ConsignmentEntry.md)

- **Source Table:** `ConsignmentEntry`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### BOMSelection

**Links from:** [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### WorksOrderSelection

**Links from:** [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### PackingInstructionFilesSelection

**Links from:** [PackingInstructionFiles](PackingInstructionFiles.md)

- **Source Table:** `PackingInstructionFiles`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### WheelCalendarSelection

**Links from:** [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### ProductMaterialOptionsSelection

**Links from:** [ProductMaterialOptions](ProductMaterialOptions.md)

- **Source Table:** `ProductMaterialOptions`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### CofCSelection

**Links from:** [CofC](CofC.md)

- **Source Table:** `CofC`
- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### ForecastSelection

**Links from:** [Forecast](Forecast.md)

- **Source Table:** `Forecast`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### QualitySystemProceduresSelection

**Links from:** [QualitySystemProcedures](QualitySystemProcedures.md)

- **Source Table:** `QualitySystemProcedures`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:23Z*
