---
layout : default
title : CofC
parent : Tables
---
# CofC

📊 **Overview:** 26 Fields | 11 Indexes | 11 Many-to-One Relations | 125 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 6
- **UUID:** 81B9B2AF685A1B4E892794C866475FCC
- **Primary Key:** 🔑 `Cert_Of_Conformance_No`
- **Generated:** 🕐 2025-11-13T02:24:51Z

---

## 📑 Table of Contents

- [📋 Fields](#fields) (26)
- [🔍 Indexes](#indexes) (11)
- [🔗 Many-to-One Relations](#many-to-one-relations) (11)
- [🔗 One-to-Many Relations](#one-to-many-relations) (125)

---

## 📋 Fields

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Cert_Of_Conformance_No** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | Test |
| Customer_Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Created_Date | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Advice_Note_No | `Date` | 🚫 Not Null | - |
| Part No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Customer_Order_No | `String` (20) | ⚠️ Required, 🚫 Not Null | - |
| MovementCofC | `Real` | 🚫 Not Null | - |
| RMC_Nos | `String` (30) | 🚫 Not Null | - |
| Delivery_Quantity | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Works_Order_No | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Petes No | `Date` | 🚫 Not Null | - |
| Quantity_Loose | `Date` | 🚫 Not Null | - |
| Price | `Boolean` | 🚫 Not Null | - |
| Nunber_Of_Boxes | `Picture` | 🚫 Not Null | - |
| Number_In_Box | `Date` | 🚫 Not Null | - |
| loose | `String` | 🚫 Not Null | - |
| Order_Completed | `Real` | 🚫 Not Null | - |
| Batch_No | `String` (5) | 🚫 Not Null | - |
| CofC_Report | `Real` | 🚫 Not Null | - |
| Invoice_Report | `Real` | 🚫 Not Null | - |
| ProductID_l | `Date` | 🚫 Not Null | - |
| Date_Int | `Date` | 🚫 Not Null | - |
| DeliveredDate_d | `Integer` | 🚫 Not Null | - |
| LocationID_l | `Date` | 🚫 Not Null | - |
| LocationName_s | `String` (30) | 🚫 Not Null | - |
| Delivery_Method_s | `String` (30) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 Cert_Of_Conformance_No

🗨️ Test

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Created_Date

**Properties:**

- **Type:** Integer
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Advice_Note_No

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Part No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Order_No

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### MovementCofC

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RMC_Nos

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Delivery_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Works_Order_No

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Petes No

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Quantity_Loose

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Price

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Nunber_Of_Boxes

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Number_In_Box

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### loose

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Order_Completed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Batch_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### CofC_Report

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Invoice_Report

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Date_Int

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DeliveredDate_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### LocationID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### LocationName_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Delivery_Method_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Cert_Of_Conformance_No` | Keywords | regular | ✨ Yes |
| `CofC_Report` | Keywords | regular | - |
| `Works_Order_No` | Keywords | regular | - |
| `Advice_Note_No` | Keywords | regular | - |
| `Date_Int` | Keywords | regular | - |
| `Customer_Code` | Keywords | regular | - |
| `Invoice_Report` | Keywords | regular | - |
| `ProductID_l` | Keywords | regular | - |
| `MovementCofC` | Keywords | regular | - |
| `Part No` | Keywords | regular | - |
| `Petes No` | Keywords | regular | - |

### Detailed Information

- **Field:** `Cert_Of_Conformance_No` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `CofC_Report`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Works_Order_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Advice_Note_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Date_Int`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer_Code`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Invoice_Report`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MovementCofC`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Part No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Petes No`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | Active |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | Active |
| `Customer_OrderEntity` | [Customer_Order](Customer_Order.md) | `Petes No` → `Petes_No` | Active |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `LocationID_l` → `StockLocationID_l` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active |
| `Advice_NoteEntity` | [Advice_Note](Advice_Note.md) | `Advice_Note_No` → `Advice_Note_No` | Active |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `LocationID_l` → `StockLocationID_l` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active |
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | Active |

### Detailed Information

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### Customer_OrderEntity

**Links to:** [Customer_Order](Customer_Order.md)

- **Source Field:** `Petes No`
- **Destination Field:** `Petes_No`
- **State:** Active

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `LocationID_l`
- **Destination Field:** `StockLocationID_l`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### Advice_NoteEntity

**Links to:** [Advice_Note](Advice_Note.md)

- **Source Field:** `Advice_Note_No`
- **Destination Field:** `Advice_Note_No`
- **State:** Active

---

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `LocationID_l`
- **Destination Field:** `StockLocationID_l`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ToolsSelection` | [Tools](Tools.md) | `ProductID` → `Product_ID` | Active |
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Product_ID` → `Product_ID` | Active |
| `OrderPickRequestSelection` | [OrderPickRequest](OrderPickRequest.md) | `PickRequestID` → `ID` | Active |
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Material_ID` → `Unique_ID` | Active |
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `ToolID` → `Tool_ID` | Active |
| `Stock_MovementSelection` | [Stock_Movement](Stock_Movement.md) | `Works_Order_No_l` → `Works_Order_No` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Product ID` → `Product_ID` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Material_ID` → `Unique_ID` | Active |
| `NonConformanceSelection` | [NonConformance](NonConformance.md) | `Tool_ID` → `Tool_ID` | Active |
| `SuppliesSelection` | [Supplies](Supplies.md) | `SupplierID_l` → `SupplierID_l` | Active |
| `PurchasesSelection` | [Purchases](Purchases.md) | `SupplierID_l` → `SupplierID_l` | Active |
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `OrderNo_l` → `OrderNo_l` | Active |
| `GaugesSelection` | [Gauges](Gauges.md) | `Product_ID` → `Product_ID` | Active |
| `GrippersSelection` | [Grippers](Grippers.md) | `Product_ID` → `Product_ID` | Active |
| `RMCSelection` | [RMC](RMC.md) | `MaterialID_l` → `Unique_ID` | Active |
| `ProductReturnWorksOrderSelection` | [ProductReturnWorksOrder](ProductReturnWorksOrder.md) | `ReturnID_l` → `ReturnID_l` | Active |
| `ProductReturnWorksOrderSelection` | [ProductReturnWorksOrder](ProductReturnWorksOrder.md) | `Works_Order_No_l` → `Works_Order_No` | Active |
| `LanguageTagSelection` | [LanguageTag](LanguageTag.md) | `Language_ID` → `ID_l` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `WorksOrder` → `Works_Order_No` | Active |
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `SuppliesID` → `UniqueID_i` | Active |
| `SuppliesSelection` | [Supplies](Supplies.md) | `PackagingCat` → `ID` | Active |
| `ToolLogSelection` | [ToolLog](ToolLog.md) | `Tool_ID` → `Tool_ID` | Active |
| `Stock_MovementSelection` | [Stock_Movement](Stock_Movement.md) | `To_Location_l` → `StockLocationID_l` | Active |
| `MaterialCheckHistorySelection` | [MaterialCheckHistory](MaterialCheckHistory.md) | `WorksOrder` → `Works_Order_No` | Active |
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `SuppliesID_i` → `UniqueID_i` | Active |
| `RealTimeSelection` | [RealTime](RealTime.md) | `WorksOrder` → `Works_Order_No` | Active |
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `ProductID` → `Product_ID` | Active |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `MatID` → `Unique_ID` | Active |
| `ProductStockTakeSelection` | [ProductStockTake](ProductStockTake.md) | `WO` → `Works_Order_No` | Active |
| `ProductStocktakeSelection` | [ProductStockTake](ProductStockTake.md) | `ProductID` → `Product_ID` | Active |
| `ConsignmentEntrySelection` | [ConsignmentEntry](ConsignmentEntry.md) | `ProductID` → `Product_ID` | Active |
| `ScrapSelection` | [Scrap](Scrap.md) | `WorksOrder` → `Works_Order_No` | Active |
| `ApprovalsSelection` | [Approvals](Approvals.md) | `ToolID` → `Tool_ID` | Active |
| `RTSUMSelection` | [RTSUM](RTSUM.md) | `WorksOrder` → `Works_Order_No` | Active |
| `RealTimeSelection` | [RealTime](RealTime.md) | `DownReason` → `ID` | Active |
| `WorkRequestCommentsSelection` | [WorkRequestComments](WorkRequestComments.md) | `WorkRequestID` → `ID` | Active |
| `BOMSelection` | [BOM](BOM.md) | `ProductID` → `Product_ID` | Active |
| `BOMSelection` | [BOM](BOM.md) | `MaterialID` → `Unique_ID` | Active |
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `NominalCode` → `ID` | Active |
| `MaterialCheckHistorySelection` | [MaterialCheckHistory](MaterialCheckHistory.md) | `MaterialID` → `Unique_ID` | Active |
| `CalibrationsSelection` | [Calibrations](Calibrations.md) | `EquipmentID` → `ID` | Active |
| `SupplierDocumentationSelection` | [SupplierDocumentation](SupplierDocumentation.md) | `SupplierID` → `SupplierID_l` | Active |
| `ProductSelection` | [Product](Product.md) | `PalletMethodID` → `ID` | Active |
| `StaffPermissionsSelection` | [StaffPermissions](StaffPermissions.md) | `PermissionID` → `ID` | Active |
| `StaffPermissionsSelection` | [StaffPermissions](StaffPermissions.md) | `StaffID` → `StaffID` | Active |
| `CalibrationProceduresSelection` | [CalibrationProcedures](CalibrationProcedures.md) | `EquipmentID` → `ID` | Active |
| `CalibrationResultsSelection` | [CalibrationResults](CalibrationResults.md) | `CalibrationID` → `ID` | Active |
| `PlanningWheelSelection` | [PlanningWheel](PlanningWheel.md) | `MaterialID` → `Unique_ID` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Customer Code` → `Customer_Code` | Active |
| `PalletSelection` | [Pallet](Pallet.md) | `ProductID` → `Product_ID` | Active |
| `LinkedBoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `LinkedBoxID` → `ID` | Active |
| `PurchaseReceiptsSelection` | [PurchaseReceipts](PurchaseReceipts.md) | `PurchaseInfoID` → `UniqueID_l` | Active |
| `RMCSelection` | [RMC](RMC.md) | `PurchaseInfoID` → `UniqueID_l` | Active |
| `PurchaseReceiptsSelection` | [PurchaseReceipts](PurchaseReceipts.md) | `RMC` → `RMCNo_l` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `ToolID` → `Tool_ID` | Active |
| `ProductSelection` | [Product](Product.md) | `EmojiID` → `ID` | Active |
| `WorkRequestsSelection` | [WorkRequests](WorkRequests.md) | `ToolID` → `Tool_ID` | Active |
| `ToolMaintenanceLogSelection` | [ToolMaintenanceLog](ToolMaintenanceLog.md) | `ToolID` → `Tool_ID` | Active |
| `ToolMaintenanceLogSelection` | [ToolMaintenanceLog](ToolMaintenanceLog.md) | `WorkRequestID` → `ID` | Active |
| `MachineMaintenanceLogSelection` | [MachineMaintenanceLog](MachineMaintenanceLog.md) | `MachineMaintenanceActionID` → `ID` | Active |
| `MachineMaintenanceRequirementsSelection` | [MachineMaintenanceRequirements](MachineMaintenanceRequirements.md) | `MachineMaintenanceActionID` → `ID` | Active |
| `DB_VariablesSelection` | [Settings](Settings.md) | `StaffID` → `StaffID` | Active |
| `PackingInstructionFilesSelection` | [PackingInstructionFiles](PackingInstructionFiles.md) | `ProductID` → `Product_ID` | Active |
| `WorkRequestCommentsSelection` | [WorkRequestComments](WorkRequestComments.md) | `StaffID` → `StaffID` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `PalletID` → `ID` | Active |
| `FirstRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `FirstRealTimeID` → `ID` | Active |
| `LastRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `LastRealTimeID` → `ID` | Active |
| `RealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `WorksOrder` → `Works_Order_No` | Active |
| `RealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `StaffID` → `StaffID` | Active |
| `RealTimeMachinesSelection` | [RealTimeMachines](RealTimeMachines.md) | `DownReason` → `ID` | Active |
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `ToolID` → `Tool_ID` | Active |
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `ZoneID` → `ID` | Active |
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `StaffID` → `StaffID` | Active |
| `PalletSelection` | [Pallet](Pallet.md) | `LocationID` → `ID` | Active |
| `LocationSelection` | [Location](Location.md) | `ParentLocationID` → `ID` | Active |
| `ToolDocumentSelection` | [ToolDocument](ToolDocument.md) | `ToolID` → `Tool_ID` | Active |
| `OrderPickRequestSelection` | [OrderPickRequest](OrderPickRequest.md) | `CustomerOrderID` → `Petes_No` | Active |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `ProductID` → `Product_ID` | Active |
| `ProductMaterialOptionsSelection` | [ProductMaterialOptions](ProductMaterialOptions.md) | `MaterialID` → `Unique_ID` | Active |
| `ProductMaterialOptionsSelection` | [ProductMaterialOptions](ProductMaterialOptions.md) | `ProductID` → `Product_ID` | Active |
| `MaterialStockTakeSelection` | [MaterialStockTake](MaterialStockTake.md) | `RMC` → `RMCNo_l` | Active |
| `MaterialCheckHistorySelection1` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC1` → `RMCNo_l` | Active |
| `MaterialCheckHistorySelection2` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC2` → `RMCNo_l` | Active |
| `MaterialCheckHistorySelection3` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC3` → `RMCNo_l` | Active |
| `PalletSelection` | [Pallet](Pallet.md) | `OrderPickRequestID` → `ID` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `OrderPickRequestID` → `ID` | Active |
| `PickRequestSelection` | [PickRequest](PickRequest.md) | `Customer` → `Customer_Code` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `CofCID` → `Cert_Of_Conformance_No` | Active |
| `PalletSelection` | [Pallet](Pallet.md) | `CofCID` → `Cert_Of_Conformance_No` | Active |
| `PickRequestSelection` | [PickRequest](PickRequest.md) | `AdviceNoteID` → `ID` | Active |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `MaterialID` → `Unique_ID` | Active |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `RMC` → `RMCNo_l` | Active |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `LocationID` → `ID` | Active |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `WorksOrder` → `Works_Order_No` | Active |
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `PrinterID` → `ID` | Active |
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `RelatedUUID` → `UUID` | Active |
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `StaffID` → `StaffID` | Active |
| `PlanningWheelSelection` | [PlanningWheel](PlanningWheel.md) | `ToolID` → `Tool_ID` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `Stock_LocationID` → `StockLocationID_l` | Active |
| `ShiftSummaryDetailSelection` | [ShiftSummaryDetail](ShiftSummaryDetail.md) | `ShiftSummaryID` → `ID` | Active |
| `ShiftSummarySelection` | [ShiftSummary](ShiftSummary.md) | `StaffID` → `StaffID` | Active |
| `ShiftSummaryDetailSelection` | [ShiftSummaryDetail](ShiftSummaryDetail.md) | `WorksOrder` → `Works_Order_No` | Active |
| `ProductSelection` | [Product](Product.md) | `DefMatID` → `Unique_ID` | Active |
| `StatusUpdatedBoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `StatusUpdatedStaffID` → `StaffID` | Active |
| `ErrorDetailSelection` | [ErrorDetail](ErrorDetail.md) | `ErrorID` → `ID` | Active |
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Product_OptionID` → `ID` | Active |
| `ForecastSelection` | [Forecast](Forecast.md) | `ProductID` → `Product_ID` | Active |
| `CustomerSelection` | [Customer](Customer.md) | `ConsignmentLocationID` → `StockLocationID_l` | Active |
| `ToolsSelection` | [Tools](Tools.md) | `HotHalfID` → `ID` | Active |
| `UsageMat1Selection` | [Material](Material.md) | `UsageMatID` → `Unique_ID` | Active |
| `UsageMat2Selection` | [Material](Material.md) | `UsageMatID2` → `Unique_ID` | Active |
| `UsageMat3Selection` | [Material](Material.md) | `UsageMatID3` → `Unique_ID` | Active |
| `QualitySystemProceduresSelection` | [QualitySystemProcedures](QualitySystemProcedures.md) | `ProductID` → `Product_ID` | Active |
| `ApprovalsSelection` | [Approvals](Approvals.md) | `Customer` → `Customer_Code` | Active |
| `BOMSelection` | [BOM](BOM.md) | `Customer` → `Customer_Code` | Active |
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `MaterialID` → `Unique_ID` | Active |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Tool ID` → `Tool_ID` | Active |
| `CustomerContactsSelection` | [CustomerContacts](CustomerContacts.md) | `Customer` → `Customer_Code` | Active |
| `CustomerSelection` | [Customer](Customer.md) | `TransportInstructionFileID` → `ID` | Active |
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `Customer` → `Customer_Code` | Active |
| `ToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `ToolID` → `Tool_ID` | Active |
| `ToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `StaffID` → `StaffID` | Active |
| `ToolNoticeWorksOrderSelection` | [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md) | `ToolNoticeID` → `ToolID` | Active |
| `ToolNoticeWorksOrderSelection` | [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |
| `DeactivatedToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `DeactivatedStaffID` → `StaffID` | Active |

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

#### OrderPickRequestSelection

**Links from:** [OrderPickRequest](OrderPickRequest.md)

- **Source Table:** `OrderPickRequest`
- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

#### Customer_OrderSelection

**Links from:** [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### WorksOrderSelection

**Links from:** [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### Stock_MovementSelection

**Links from:** [Stock_Movement](Stock_Movement.md)

- **Source Table:** `Stock_Movement`
- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### NonConformanceSelection

**Links from:** [NonConformance](NonConformance.md)

- **Source Table:** `NonConformance`
- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### SuppliesSelection

**Links from:** [Supplies](Supplies.md)

- **Source Table:** `Supplies`
- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** Active

---

#### PurchasesSelection

**Links from:** [Purchases](Purchases.md)

- **Source Table:** `Purchases`
- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** Active

---

#### PurchaseInfoSelection

**Links from:** [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `OrderNo_l`
- **This Table Field:** `OrderNo_l`
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

#### RMCSelection

**Links from:** [RMC](RMC.md)

- **Source Table:** `RMC`
- **Source Field:** `MaterialID_l`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### ProductReturnWorksOrderSelection

**Links from:** [ProductReturnWorksOrder](ProductReturnWorksOrder.md)

- **Source Table:** `ProductReturnWorksOrder`
- **Source Field:** `ReturnID_l`
- **This Table Field:** `ReturnID_l`
- **State:** Active

---

#### ProductReturnWorksOrderSelection

**Links from:** [ProductReturnWorksOrder](ProductReturnWorksOrder.md)

- **Source Table:** `ProductReturnWorksOrder`
- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### LanguageTagSelection

**Links from:** [LanguageTag](LanguageTag.md)

- **Source Table:** `LanguageTag`
- **Source Field:** `Language_ID`
- **This Table Field:** `ID_l`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ProductPackagingSelection

**Links from:** [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `SuppliesID`
- **This Table Field:** `UniqueID_i`
- **State:** Active

---

#### SuppliesSelection

**Links from:** [Supplies](Supplies.md)

- **Source Table:** `Supplies`
- **Source Field:** `PackagingCat`
- **This Table Field:** `ID`
- **State:** Active

---

#### ToolLogSelection

**Links from:** [ToolLog](ToolLog.md)

- **Source Table:** `ToolLog`
- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### Stock_MovementSelection

**Links from:** [Stock_Movement](Stock_Movement.md)

- **Source Table:** `Stock_Movement`
- **Source Field:** `To_Location_l`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

#### MaterialCheckHistorySelection

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### PurchaseInfoSelection

**Links from:** [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`
- **State:** Active

---

#### RealTimeSelection

**Links from:** [RealTime](RealTime.md)

- **Source Table:** `RealTime`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ProductPackagingSelection

**Links from:** [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### WheelCalendarSelection

**Links from:** [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### ProductStockTakeSelection

**Links from:** [ProductStockTake](ProductStockTake.md)

- **Source Table:** `ProductStockTake`
- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`
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

#### ScrapSelection

**Links from:** [Scrap](Scrap.md)

- **Source Table:** `Scrap`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ApprovalsSelection

**Links from:** [Approvals](Approvals.md)

- **Source Table:** `Approvals`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### RTSUMSelection

**Links from:** [RTSUM](RTSUM.md)

- **Source Table:** `RTSUM`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### RealTimeSelection

**Links from:** [RealTime](RealTime.md)

- **Source Table:** `RealTime`
- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** Active

---

#### WorkRequestCommentsSelection

**Links from:** [WorkRequestComments](WorkRequestComments.md)

- **Source Table:** `WorkRequestComments`
- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

#### BOMSelection

**Links from:** [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### BOMSelection

**Links from:** [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### PurchaseInfoSelection

**Links from:** [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `NominalCode`
- **This Table Field:** `ID`
- **State:** Active

---

#### MaterialCheckHistorySelection

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### CalibrationsSelection

**Links from:** [Calibrations](Calibrations.md)

- **Source Table:** `Calibrations`
- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** Active

---

#### SupplierDocumentationSelection

**Links from:** [SupplierDocumentation](SupplierDocumentation.md)

- **Source Table:** `SupplierDocumentation`
- **Source Field:** `SupplierID`
- **This Table Field:** `SupplierID_l`
- **State:** Active

---

#### ProductSelection

**Links from:** [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `PalletMethodID`
- **This Table Field:** `ID`
- **State:** Active

---

#### StaffPermissionsSelection

**Links from:** [StaffPermissions](StaffPermissions.md)

- **Source Table:** `StaffPermissions`
- **Source Field:** `PermissionID`
- **This Table Field:** `ID`
- **State:** Active

---

#### StaffPermissionsSelection

**Links from:** [StaffPermissions](StaffPermissions.md)

- **Source Table:** `StaffPermissions`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### CalibrationProceduresSelection

**Links from:** [CalibrationProcedures](CalibrationProcedures.md)

- **Source Table:** `CalibrationProcedures`
- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** Active

---

#### CalibrationResultsSelection

**Links from:** [CalibrationResults](CalibrationResults.md)

- **Source Table:** `CalibrationResults`
- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`
- **State:** Active

---

#### PlanningWheelSelection

**Links from:** [PlanningWheel](PlanningWheel.md)

- **Source Table:** `PlanningWheel`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### LinkedBoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `LinkedBoxID`
- **This Table Field:** `ID`
- **State:** Active

---

#### PurchaseReceiptsSelection

**Links from:** [PurchaseReceipts](PurchaseReceipts.md)

- **Source Table:** `PurchaseReceipts`
- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** Active

---

#### RMCSelection

**Links from:** [RMC](RMC.md)

- **Source Table:** `RMC`
- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** Active

---

#### PurchaseReceiptsSelection

**Links from:** [PurchaseReceipts](PurchaseReceipts.md)

- **Source Table:** `PurchaseReceipts`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ProductSelection

**Links from:** [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `EmojiID`
- **This Table Field:** `ID`
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

#### ToolMaintenanceLogSelection

**Links from:** [ToolMaintenanceLog](ToolMaintenanceLog.md)

- **Source Table:** `ToolMaintenanceLog`
- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

#### MachineMaintenanceLogSelection

**Links from:** [MachineMaintenanceLog](MachineMaintenanceLog.md)

- **Source Table:** `MachineMaintenanceLog`
- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** Active

---

#### MachineMaintenanceRequirementsSelection

**Links from:** [MachineMaintenanceRequirements](MachineMaintenanceRequirements.md)

- **Source Table:** `MachineMaintenanceRequirements`
- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** Active

---

#### DB_VariablesSelection

**Links from:** [Settings](Settings.md)

- **Source Table:** `Settings`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### PackingInstructionFilesSelection

**Links from:** [PackingInstructionFiles](PackingInstructionFiles.md)

- **Source Table:** `PackingInstructionFiles`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### WorkRequestCommentsSelection

**Links from:** [WorkRequestComments](WorkRequestComments.md)

- **Source Table:** `WorkRequestComments`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `PalletID`
- **This Table Field:** `ID`
- **State:** Active

---

#### FirstRealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`
- **State:** Active

---

#### LastRealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`
- **State:** Active

---

#### RealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### RealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### RealTimeMachinesSelection

**Links from:** [RealTimeMachines](RealTimeMachines.md)

- **Source Table:** `RealTimeMachines`
- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** Active

---

#### ToolTemperatureTargetSelection

**Links from:** [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ToolTemperatureTargetSelection

**Links from:** [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `ZoneID`
- **This Table Field:** `ID`
- **State:** Active

---

#### ToolTemperatureTargetSelection

**Links from:** [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** Active

---

#### LocationSelection

**Links from:** [Location](Location.md)

- **Source Table:** `Location`
- **Source Field:** `ParentLocationID`
- **This Table Field:** `ID`
- **State:** Active

---

#### ToolDocumentSelection

**Links from:** [ToolDocument](ToolDocument.md)

- **Source Table:** `ToolDocument`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### OrderPickRequestSelection

**Links from:** [OrderPickRequest](OrderPickRequest.md)

- **Source Table:** `OrderPickRequest`
- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`
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
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### ProductMaterialOptionsSelection

**Links from:** [ProductMaterialOptions](ProductMaterialOptions.md)

- **Source Table:** `ProductMaterialOptions`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### MaterialStockTakeSelection

**Links from:** [MaterialStockTake](MaterialStockTake.md)

- **Source Table:** `MaterialStockTake`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialCheckHistorySelection1

🗨️ Relationship comment test

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC1`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialCheckHistorySelection2

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC2`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialCheckHistorySelection3

**Links from:** [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC3`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

#### PickRequestSelection

**Links from:** [PickRequest](PickRequest.md)

- **Source Table:** `PickRequest`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** Active

---

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** Active

---

#### PickRequestSelection

**Links from:** [PickRequest](PickRequest.md)

- **Source Table:** `PickRequest`
- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`
- **State:** Active

---

#### MaterialStockSelection

**Links from:** [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### MaterialStockSelection

**Links from:** [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** Active

---

#### MaterialStockSelection

**Links from:** [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** Active

---

#### WheelCalendarSelection

**Links from:** [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### PrintJobSelection

**Links from:** [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `PrinterID`
- **This Table Field:** `ID`
- **State:** Active

---

#### PrintJobSelection

**Links from:** [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `RelatedUUID`
- **This Table Field:** `UUID`
- **State:** Active

---

#### PrintJobSelection

**Links from:** [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### PlanningWheelSelection

**Links from:** [PlanningWheel](PlanningWheel.md)

- **Source Table:** `PlanningWheel`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

#### ShiftSummaryDetailSelection

**Links from:** [ShiftSummaryDetail](ShiftSummaryDetail.md)

- **Source Table:** `ShiftSummaryDetail`
- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`
- **State:** Active

---

#### ShiftSummarySelection

**Links from:** [ShiftSummary](ShiftSummary.md)

- **Source Table:** `ShiftSummary`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### ShiftSummaryDetailSelection

**Links from:** [ShiftSummaryDetail](ShiftSummaryDetail.md)

- **Source Table:** `ShiftSummaryDetail`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### ProductSelection

**Links from:** [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### StatusUpdatedBoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### ErrorDetailSelection

**Links from:** [ErrorDetail](ErrorDetail.md)

- **Source Table:** `ErrorDetail`
- **Source Field:** `ErrorID`
- **This Table Field:** `ID`
- **State:** Active

---

#### Customer_OrderSelection

**Links from:** [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`
- **State:** Active

---

#### ForecastSelection

**Links from:** [Forecast](Forecast.md)

- **Source Table:** `Forecast`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### CustomerSelection

**Links from:** [Customer](Customer.md)

- **Source Table:** `Customer`
- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

#### ToolsSelection

**Links from:** [Tools](Tools.md)

- **Source Table:** `Tools`
- **Source Field:** `HotHalfID`
- **This Table Field:** `ID`
- **State:** Active

---

#### UsageMat1Selection

**Links from:** [Material](Material.md)

- **Source Table:** `Material`
- **Source Field:** `UsageMatID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### UsageMat2Selection

**Links from:** [Material](Material.md)

- **Source Table:** `Material`
- **Source Field:** `UsageMatID2`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### UsageMat3Selection

**Links from:** [Material](Material.md)

- **Source Table:** `Material`
- **Source Field:** `UsageMatID3`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### QualitySystemProceduresSelection

**Links from:** [QualitySystemProcedures](QualitySystemProcedures.md)

- **Source Table:** `QualitySystemProcedures`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** Active

---

#### ApprovalsSelection

**Links from:** [Approvals](Approvals.md)

- **Source Table:** `Approvals`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### BOMSelection

**Links from:** [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### WorksOrderSelection

**Links from:** [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** Active

---

#### Product_OptionSelection

**Links from:** [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Tool ID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### CustomerContactsSelection

**Links from:** [CustomerContacts](CustomerContacts.md)

- **Source Table:** `CustomerContacts`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### CustomerSelection

**Links from:** [Customer](Customer.md)

- **Source Table:** `Customer`
- **Source Field:** `TransportInstructionFileID`
- **This Table Field:** `ID`
- **State:** Active

---

#### ProductPackagingSelection

**Links from:** [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** Active

---

#### ToolNoticeSelection

**Links from:** [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** Active

---

#### ToolNoticeSelection

**Links from:** [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### ToolNoticeWorksOrderSelection

**Links from:** [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md)

- **Source Table:** `ToolNoticeWorksOrder`
- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`
- **State:** Active

---

#### ToolNoticeWorksOrderSelection

**Links from:** [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md)

- **Source Table:** `ToolNoticeWorksOrder`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** Active

---

#### DeactivatedToolNoticeSelection

**Links from:** [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:24:51Z*
