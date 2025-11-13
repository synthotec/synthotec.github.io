---
layout : default
title : WorksOrder
parent : Tables
---
# WorksOrder

📊 **Overview:** 85 Fields | 18 Indexes | 22 Many-to-One Relations | 114 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 4
- **UUID:** 305DC4E1E3339443B76C086981BBCB7C
- **Primary Key:** 🔑 `Works_Order_No`
- **Generated:** 🕐 2025-11-12T23:08:46Z

---

## 📑 Table of Contents

- [📋 Fields](#fields) (85)
- [🔍 Indexes](#indexes) (18)
- [🔗 Many-to-One Relations](#many-to-one-relations) (22)
- [🔗 One-to-Many Relations](#one-to-many-relations) (114)

---

## 📋 Fields

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
| `OEEgenerated` | - | regular | - |
| `Raised_Job_Card` | - | regular | - |
| `Machine_Started` | - | regular | - |
| `MaterialID` | - | regular | - |
| `No_In_Stock` | - | regular | - |
| `NewSystem` | - | regular | - |
| `Machine_No` | - | regular | - |
| `Part_No` | - | regular | - |
| `Customer_Code` | - | regular | - |
| `Works_Order_No` | - | regular | ✨ Yes |
| `ToolID` | - | regular | - |
| `Issue_No` | - | regular | - |
| `Machine_Completed` | - | regular | - |
| `ProductID_l` | - | regular | - |
| `Packing_Completed` | - | regular | - |
| `Robot` | - | regular | - |
| `MigrationID` | - | regular | - |
| `AutomaticStock` | - | regular | - |

### Detailed Information

- **Field:** `OEEgenerated`
  - **Kind:** regular
- **Field:** `Raised_Job_Card`
  - **Kind:** regular
- **Field:** `Machine_Started`
  - **Kind:** regular
- **Field:** `MaterialID`
  - **Kind:** regular
- **Field:** `No_In_Stock`
  - **Kind:** regular
- **Field:** `NewSystem`
  - **Kind:** regular
- **Field:** `Machine_No`
  - **Kind:** regular
- **Field:** `Part_No`
  - **Kind:** regular
- **Field:** `Customer_Code`
  - **Kind:** regular
- **Field:** `Works_Order_No` ✨ **(Unique)**
  - **Kind:** regular
- **Field:** `ToolID`
  - **Kind:** regular
- **Field:** `Issue_No`
  - **Kind:** regular
- **Field:** `Machine_Completed`
  - **Kind:** regular
- **Field:** `ProductID_l`
  - **Kind:** regular
- **Field:** `Packing_Completed`
  - **Kind:** regular
- **Field:** `Robot`
  - **Kind:** regular
- **Field:** `MigrationID`
  - **Kind:** regular
- **Field:** `AutomaticStock`
  - **Kind:** regular

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | - |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | - |
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |

### Detailed Information

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`

---

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ToolsSelection` | - | `ProductID` → `Product_ID` | - |
| `Customer_OrderSelection` | - | `Product_ID` → `Product_ID` | - |
| `OrderPickRequestSelection` | - | `PickRequestID` → `ID` | - |
| `Customer_OrderSelection` | - | `Material_ID` → `Unique_ID` | - |
| `Stock_MovementSelection` | - | `Works_Order_No_l` → `Works_Order_No` | - |
| `CofCSelection` | - | `Petes No` → `Petes_No` | - |
| `Product_OptionSelection` | - | `Product ID` → `Product_ID` | - |
| `Product_OptionSelection` | - | `Material_ID` → `Unique_ID` | - |
| `NonConformanceSelection` | - | `Tool_ID` → `Tool_ID` | - |
| `SuppliesSelection` | - | `SupplierID_l` → `SupplierID_l` | - |
| `PurchasesSelection` | - | `SupplierID_l` → `SupplierID_l` | - |
| `PurchaseInfoSelection` | - | `OrderNo_l` → `OrderNo_l` | - |
| `GaugesSelection` | - | `Product_ID` → `Product_ID` | - |
| `GrippersSelection` | - | `Product_ID` → `Product_ID` | - |
| `RMCSelection` | - | `MaterialID_l` → `Unique_ID` | - |
| `ProductReturnWorksOrderSelection` | - | `ReturnID_l` → `ReturnID_l` | - |
| `ProductReturnWorksOrderSelection` | - | `Works_Order_No_l` → `Works_Order_No` | - |
| `LanguageTagSelection` | - | `Language_ID` → `ID_l` | - |
| `BoxLabelsSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductPackagingSelection` | - | `SuppliesID` → `UniqueID_i` | - |
| `SuppliesSelection` | - | `PackagingCat` → `ID` | - |
| `ToolLogSelection` | - | `Tool_ID` → `Tool_ID` | - |
| `Stock_MovementSelection` | - | `To_Location_l` → `StockLocationID_l` | - |
| `MaterialCheckHistorySelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `PurchaseInfoSelection` | - | `SuppliesID_i` → `UniqueID_i` | - |
| `RealTimeSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductPackagingSelection` | - | `ProductID` → `Product_ID` | - |
| `WheelCalendarSelection` | - | `MatID` → `Unique_ID` | - |
| `ProductStockTakeSelection` | - | `WO` → `Works_Order_No` | - |
| `ProductStocktakeSelection` | - | `ProductID` → `Product_ID` | - |
| `ConsignmentEntrySelection` | - | `ProductID` → `Product_ID` | - |
| `ScrapSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `RTSUMSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `RealTimeSelection` | - | `DownReason` → `ID` | - |
| `WorkRequestCommentsSelection` | - | `WorkRequestID` → `ID` | - |
| `BOMSelection` | - | `ProductID` → `Product_ID` | - |
| `PurchaseInfoSelection` | - | `NominalCode` → `ID` | - |
| `CalibrationsSelection` | - | `EquipmentID` → `ID` | - |
| `SupplierDocumentationSelection` | - | `SupplierID` → `SupplierID_l` | - |
| `ProductSelection` | - | `PalletMethodID` → `ID` | - |
| `StaffPermissionsSelection` | - | `PermissionID` → `ID` | - |
| `StaffPermissionsSelection` | - | `StaffID` → `StaffID` | - |
| `CalibrationProceduresSelection` | - | `EquipmentID` → `ID` | - |
| `CalibrationResultsSelection` | - | `CalibrationID` → `ID` | - |
| `Product_OptionSelection` | - | `Customer Code` → `Customer_Code` | - |
| `Finished_StockSelection` | - | `LocationID_l` → `StockLocationID_l` | - |
| `PalletSelection` | - | `ProductID` → `Product_ID` | - |
| `LinkedBoxLabelsSelection` | - | `LinkedBoxID` → `ID` | - |
| `PurchaseReceiptsSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `RMCSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `PurchaseReceiptsSelection` | - | `RMC` → `RMCNo_l` | - |
| `ProductSelection` | - | `EmojiID` → `ID` | - |
| `ToolMaintenanceLogSelection` | - | `WorkRequestID` → `ID` | - |
| `MachineMaintenanceLogSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `MachineMaintenanceRequirementsSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `DB_VariablesSelection` | - | `StaffID` → `StaffID` | - |
| `PackingInstructionFilesSelection` | - | `ProductID` → `Product_ID` | - |
| `WorkRequestCommentsSelection` | - | `StaffID` → `StaffID` | - |
| `BoxLabelsSelection` | - | `PalletID` → `ID` | - |
| `FirstRealTimeSensorExceptionsSelection` | - | `FirstRealTimeID` → `ID` | - |
| `LastRealTimeSensorExceptionsSelection` | - | `LastRealTimeID` → `ID` | - |
| `RealTimeSensorExceptionsSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `RealTimeSensorExceptionsSelection` | - | `StaffID` → `StaffID` | - |
| `RealTimeMachinesSelection` | - | `DownReason` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `ZoneID` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `StaffID` → `StaffID` | - |
| `PalletSelection` | - | `LocationID` → `ID` | - |
| `LocationSelection` | - | `ParentLocationID` → `ID` | - |
| `OrderPickRequestSelection` | - | `CustomerOrderID` → `Petes_No` | - |
| `WheelCalendarSelection` | - | `ProductID` → `Product_ID` | - |
| `ProductMaterialOptionsSelection` | - | `ProductID` → `Product_ID` | - |
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
| `PickRequestSelection` | - | `AdviceNoteID` → `ID` | - |
| `MaterialStockSelection` | - | `RMC` → `RMCNo_l` | - |
| `MaterialStockSelection` | - | `LocationID` → `ID` | - |
| `WheelCalendarSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `PrintJobSelection` | - | `PrinterID` → `ID` | - |
| `PrintJobSelection` | - | `RelatedUUID` → `UUID` | - |
| `PrintJobSelection` | - | `StaffID` → `StaffID` | - |
| `BoxLabelsSelection` | - | `Stock_LocationID` → `StockLocationID_l` | - |
| `ShiftSummaryDetailSelection` | - | `ShiftSummaryID` → `ID` | - |
| `ShiftSummarySelection` | - | `StaffID` → `StaffID` | - |
| `ShiftSummaryDetailSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductSelection` | - | `DefMatID` → `Unique_ID` | - |
| `StatusUpdatedBoxLabelsSelection` | - | `StatusUpdatedStaffID` → `StaffID` | - |
| `ErrorDetailSelection` | - | `ErrorID` → `ID` | - |
| `Customer_OrderSelection` | - | `Product_OptionID` → `ID` | - |
| `ForecastSelection` | - | `ProductID` → `Product_ID` | - |
| `CustomerSelection` | - | `ConsignmentLocationID` → `StockLocationID_l` | - |
| `ToolsSelection` | - | `HotHalfID` → `ID` | - |
| `UsageMat1Selection` | - | `UsageMatID` → `Unique_ID` | - |
| `UsageMat2Selection` | - | `UsageMatID2` → `Unique_ID` | - |
| `UsageMat3Selection` | - | `UsageMatID3` → `Unique_ID` | - |
| `QualitySystemProceduresSelection` | - | `ProductID` → `Product_ID` | - |
| `ApprovalsSelection` | - | `Customer` → `Customer_Code` | - |
| `BOMSelection` | - | `Customer` → `Customer_Code` | - |
| `Product_OptionSelection` | - | `Tool ID` → `Tool_ID` | - |
| `CustomerContactsSelection` | - | `Customer` → `Customer_Code` | - |
| `CustomerSelection` | - | `TransportInstructionFileID` → `ID` | - |
| `ProductPackagingSelection` | - | `Customer` → `Customer_Code` | - |
| `ToolNoticeSelection` | - | `StaffID` → `StaffID` | - |
| `ToolNoticeWorksOrderSelection` | - | `ToolNoticeID` → `ToolID` | - |
| `ToolNoticeWorksOrderSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `DeactivatedToolNoticeSelection` | - | `DeactivatedStaffID` → `StaffID` | - |

### Detailed Information

#### ToolsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

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

#### Stock_MovementSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

---

#### CofCSelection

- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`

---

#### Product_OptionSelection

- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`

---

#### Product_OptionSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`

---

#### NonConformanceSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`

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

#### ToolLogSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`

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

#### ProductPackagingSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### WheelCalendarSelection

- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`

---

#### ProductStockTakeSelection

- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`

---

#### ProductStocktakeSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ConsignmentEntrySelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ScrapSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

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

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### PurchaseInfoSelection

- **Source Field:** `NominalCode`
- **This Table Field:** `ID`

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

#### Product_OptionSelection

- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`

---

#### Finished_StockSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`

---

#### PalletSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

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

#### ProductSelection

- **Source Field:** `EmojiID`
- **This Table Field:** `ID`

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

#### PackingInstructionFilesSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

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

#### OrderPickRequestSelection

- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`

---

#### WheelCalendarSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ProductMaterialOptionsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

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

#### PickRequestSelection

- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`

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

#### ForecastSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### CustomerSelection

- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`

---

#### ToolsSelection

- **Source Field:** `HotHalfID`
- **This Table Field:** `ID`

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

#### QualitySystemProceduresSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ApprovalsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### BOMSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

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
*Generated at: 2025-11-12T23:08:46Z*
