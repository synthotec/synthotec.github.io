---
layout : default
title : BoxLabels
parent : Tables
---
# BoxLabels

📊 **Overview:** 36 Fields | 19 Indexes | 26 Many-to-One Relations | 110 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 76
- **UUID:** 0B40C76291EE2E44AC3F733AD8213391
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-12T23:11:38Z

---

## 📑 Table of Contents

- [📋 Fields](#fields) (36)
- [🔍 Indexes](#indexes) (19)
- [🔗 Many-to-One Relations](#many-to-one-relations) (26)
- [🔗 One-to-Many Relations](#one-to-many-relations) (110)

---

## 📋 Fields

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| BoxNumber | `Date` | 🚫 Not Null | - |
| RouteCard | `Picture` | 🚫 Not Null | - |
| PackedBy | `String` (255) | 🚫 Not Null | - |
| Date | `Integer` | 🚫 Not Null | - |
| Time | `Long Integer` | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Parts | `Date` | 🚫 Not Null | - |
| Shift | `Date` | 🚫 Not Null | - |
| WORC | `Date` | 🚫 Not Null | - |
| Mandrels | `Picture` | 🚫 Not Null | - |
| NotMade | `Real` | 🚫 Not Null | - |
| NotMadeWho | `String` (255) | 🚫 Not Null | - |
| TimeToPack | `Boolean` | 🚫 Not Null | - |
| StockInput | `Real` | 🚫 Not Null | - |
| TimeProcessed | `Real` | 🚫 Not Null | - |
| StandardHours | `Boolean` | 🚫 Not Null | - |
| ShiftDate | `Date` | 🚫 Not Null | - |
| PartBoxCode | `String` (5) | 🚫 Not Null | - |
| LinkedBoxID | `Date` | 🚫 Not Null | - |
| RemoveFromStock | `Real` | 🚫 Not Null | - |
| StockRemovedBy | `String` | 🚫 Not Null | - |
| PalletID | `Date` | 🚫 Not Null | - |
| WhenAddedToPallet | `String` (255) | - | - |
| OrderPickRequestID | `Date` | - | - |
| Version | `Picture` | - | - |
| CofCID | `Date` | - | - |
| Stock_LocationID | `Date` | - | - |
| Comments | `String` | - | - |
| StatusUpdatedStaffID | `Date` | - | - |
| StatusUpdatedWhen | `String` (255) | - | - |
| UUID | `String` | - | - |
| MigrationID | `Date` | - | - |
| LastMigration | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### BoxNumber

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RouteCard

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### PackedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Time

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### DateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Parts

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Shift

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WORC

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Mandrels

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NotMade

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NotMadeWho

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### TimeToPack

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### StockInput

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### TimeProcessed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### StandardHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### ShiftDate

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PartBoxCode

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### LinkedBoxID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RemoveFromStock

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### StockRemovedBy

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### PalletID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### WhenAddedToPallet

**Properties:**

- **Type:** String (max length: 255)

---

#### OrderPickRequestID

**Properties:**

- **Type:** Date

---

#### Version

**Properties:**

- **Type:** Picture

---

#### CofCID

**Properties:**

- **Type:** Date

---

#### Stock_LocationID

**Properties:**

- **Type:** Date

---

#### Comments

**Properties:**

- **Type:** String

---

#### StatusUpdatedStaffID

**Properties:**

- **Type:** Date

---

#### StatusUpdatedWhen

**Properties:**

- **Type:** String (max length: 255)

---

#### UUID

**Properties:**

- **Type:** String

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
| `PalletID` | - | regular | - |
| `WorksOrder` | - | regular | - |
| `UUID` | - | regular | - |
| `ToolID` | - | regular | - |
| `ID` | - | regular | ✨ Yes |
| `Shift` | - | regular | - |
| `StockRemovedBy` | - | regular | - |
| `RemoveFromStock` | - | regular | - |
| `Stock_LocationID` | - | regular | - |
| `LinkedBoxID` | - | regular | - |
| `TimeProcessed` | - | regular | - |
| `PackedBy` | - | regular | - |
| `CofCID` | - | regular | - |
| `Version` | - | regular | - |
| `StockInput` | - | regular | - |
| `OrderPickRequestID` | - | regular | - |
| `ShiftDate` | - | regular | - |
| `PartBoxCode` | - | regular | - |
| `NotMade` | - | regular | - |

### Detailed Information

- **Field:** `PalletID`
  - **Kind:** regular
- **Field:** `WorksOrder`
  - **Kind:** regular
- **Field:** `UUID`
  - **Kind:** regular
- **Field:** `ToolID`
  - **Kind:** regular
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
- **Field:** `Shift`
  - **Kind:** regular
- **Field:** `StockRemovedBy`
  - **Kind:** regular
- **Field:** `RemoveFromStock`
  - **Kind:** regular
- **Field:** `Stock_LocationID`
  - **Kind:** regular
- **Field:** `LinkedBoxID`
  - **Kind:** regular
- **Field:** `TimeProcessed`
  - **Kind:** regular
- **Field:** `PackedBy`
  - **Kind:** regular
- **Field:** `CofCID`
  - **Kind:** regular
- **Field:** `Version`
  - **Kind:** regular
- **Field:** `StockInput`
  - **Kind:** regular
- **Field:** `OrderPickRequestID`
  - **Kind:** regular
- **Field:** `ShiftDate`
  - **Kind:** regular
- **Field:** `PartBoxCode`
  - **Kind:** regular
- **Field:** `NotMade`
  - **Kind:** regular

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `LinkedBoxLabelsEntity` | [BoxLabels](BoxLabels.md) | `LinkedBoxID` → `ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `PalletEntity` | [Pallet](Pallet.md) | `PalletID` → `ID` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `OrderPickRequestEntity` | [OrderPickRequest](OrderPickRequest.md) | `OrderPickRequestID` → `ID` | - |
| `OrderPickRequestEntity` | [OrderPickRequest](OrderPickRequest.md) | `OrderPickRequestID` → `ID` | - |
| `CofCEntity` | [CofC](CofC.md) | `CofCID` → `Cert_Of_Conformance_No` | - |
| `CofCEntity` | [CofC](CofC.md) | `CofCID` → `Cert_Of_Conformance_No` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `Stock_LocationID` → `StockLocationID_l` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |
| `StatusUpdatedStaffEntity` | [Staff](Staff.md) | `StatusUpdatedStaffID` → `StaffID` | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | - |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

#### LinkedBoxLabelsEntity

**Links to:** [BoxLabels](BoxLabels.md)

- **Source Field:** `LinkedBoxID`
- **Destination Field:** `ID`

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

#### PalletEntity

**Links to:** [Pallet](Pallet.md)

- **Source Field:** `PalletID`
- **Destination Field:** `ID`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

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

#### OrderPickRequestEntity

**Links to:** [OrderPickRequest](OrderPickRequest.md)

- **Source Field:** `OrderPickRequestID`
- **Destination Field:** `ID`

---

#### OrderPickRequestEntity

**Links to:** [OrderPickRequest](OrderPickRequest.md)

- **Source Field:** `OrderPickRequestID`
- **Destination Field:** `ID`

---

#### CofCEntity

**Links to:** [CofC](CofC.md)

- **Source Field:** `CofCID`
- **Destination Field:** `Cert_Of_Conformance_No`

---

#### CofCEntity

**Links to:** [CofC](CofC.md)

- **Source Field:** `CofCID`
- **Destination Field:** `Cert_Of_Conformance_No`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `Stock_LocationID`
- **Destination Field:** `StockLocationID_l`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

#### StatusUpdatedStaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StatusUpdatedStaffID`
- **Destination Field:** `StaffID`

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ToolsSelection` | - | `ProductID` → `Product_ID` | - |
| `Customer_OrderSelection` | - | `Product_ID` → `Product_ID` | - |
| `OrderPickRequestSelection` | - | `PickRequestID` → `ID` | - |
| `Customer_OrderSelection` | - | `Material_ID` → `Unique_ID` | - |
| `WorksOrderSelection` | - | `Customer_Code` → `Customer_Code` | - |
| `Stock_MovementSelection` | - | `Works_Order_No_l` → `Works_Order_No` | - |
| `CofCSelection` | - | `Works_Order_No` → `Works_Order_No` | - |
| `CofCSelection` | - | `Petes No` → `Petes_No` | - |
| `Finished_StockSelection` | - | `Works_Order_No` → `Works_Order_No` | - |
| `Product_OptionSelection` | - | `Product ID` → `Product_ID` | - |
| `Product_OptionSelection` | - | `Material_ID` → `Unique_ID` | - |
| `NonConformanceSelection` | - | `Tool_ID` → `Tool_ID` | - |
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
| `ProductPackagingSelection` | - | `SuppliesID` → `UniqueID_i` | - |
| `SuppliesSelection` | - | `PackagingCat` → `ID` | - |
| `ToolLogSelection` | - | `Tool_ID` → `Tool_ID` | - |
| `Stock_MovementSelection` | - | `To_Location_l` → `StockLocationID_l` | - |
| `PurchaseInfoSelection` | - | `SuppliesID_i` → `UniqueID_i` | - |
| `ProductPackagingSelection` | - | `ProductID` → `Product_ID` | - |
| `WheelCalendarSelection` | - | `MatID` → `Unique_ID` | - |
| `ProductStockTakeSelection` | - | `WO` → `Works_Order_No` | - |
| `ProductStocktakeSelection` | - | `ProductID` → `Product_ID` | - |
| `ConsignmentEntrySelection` | - | `ProductID` → `Product_ID` | - |
| `RealTimeSelection` | - | `DownReason` → `ID` | - |
| `WorkRequestCommentsSelection` | - | `WorkRequestID` → `ID` | - |
| `BOMSelection` | - | `ProductID` → `Product_ID` | - |
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
| `PalletSelection` | - | `ProductID` → `Product_ID` | - |
| `PurchaseReceiptsSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `RMCSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `PurchaseReceiptsSelection` | - | `RMC` → `RMCNo_l` | - |
| `WorksOrderSelection` | - | `ProductID_l` → `Product_ID` | - |
| `ProductSelection` | - | `EmojiID` → `ID` | - |
| `ToolMaintenanceLogSelection` | - | `WorkRequestID` → `ID` | - |
| `MachineMaintenanceLogSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `MachineMaintenanceRequirementsSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `DB_VariablesSelection` | - | `StaffID` → `StaffID` | - |
| `PackingInstructionFilesSelection` | - | `ProductID` → `Product_ID` | - |
| `WorkRequestCommentsSelection` | - | `StaffID` → `StaffID` | - |
| `FirstRealTimeSensorExceptionsSelection` | - | `FirstRealTimeID` → `ID` | - |
| `LastRealTimeSensorExceptionsSelection` | - | `LastRealTimeID` → `ID` | - |
| `RealTimeSensorExceptionsSelection` | - | `StaffID` → `StaffID` | - |
| `RealTimeMachinesSelection` | - | `DownReason` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `ZoneID` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `StaffID` → `StaffID` | - |
| `PalletSelection` | - | `LocationID` → `ID` | - |
| `LocationSelection` | - | `ParentLocationID` → `ID` | - |
| `OrderPickRequestSelection` | - | `CustomerOrderID` → `Petes_No` | - |
| `WheelCalendarSelection` | - | `ProductID` → `Product_ID` | - |
| `ProductMaterialOptionsSelection` | - | `MaterialID` → `Unique_ID` | - |
| `ProductMaterialOptionsSelection` | - | `ProductID` → `Product_ID` | - |
| `MaterialStockTakeSelection` | - | `RMC` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection1` | - | `RMC1` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection2` | - | `RMC2` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection3` | - | `RMC3` → `RMCNo_l` | - |
| `PickRequestSelection` | - | `Customer` → `Customer_Code` | - |
| `CofCSelection` | - | `Advice_Note_No` → `Advice_Note_No` | - |
| `CofCSelection` | - | `LocationID_l` → `StockLocationID_l` | - |
| `CofCSelection` | - | `ProductID_l` → `Product_ID` | - |
| `PickRequestSelection` | - | `AdviceNoteID` → `ID` | - |
| `Customer_OrderSelection` | - | `Customer_Code` → `Customer_Code` | - |
| `MaterialStockSelection` | - | `MaterialID` → `Unique_ID` | - |
| `MaterialStockSelection` | - | `RMC` → `RMCNo_l` | - |
| `MaterialStockSelection` | - | `LocationID` → `ID` | - |
| `PrintJobSelection` | - | `PrinterID` → `ID` | - |
| `PrintJobSelection` | - | `RelatedUUID` → `UUID` | - |
| `PrintJobSelection` | - | `StaffID` → `StaffID` | - |
| `ShiftSummaryDetailSelection` | - | `ShiftSummaryID` → `ID` | - |
| `ShiftSummarySelection` | - | `StaffID` → `StaffID` | - |
| `ProductSelection` | - | `DefMatID` → `Unique_ID` | - |
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
| `WorksOrderSelection` | - | `MaterialID` → `Unique_ID` | - |
| `Product_OptionSelection` | - | `Tool ID` → `Tool_ID` | - |
| `CustomerContactsSelection` | - | `Customer` → `Customer_Code` | - |
| `CustomerSelection` | - | `TransportInstructionFileID` → `ID` | - |
| `ProductPackagingSelection` | - | `Customer` → `Customer_Code` | - |
| `ToolNoticeSelection` | - | `StaffID` → `StaffID` | - |
| `ToolNoticeWorksOrderSelection` | - | `ToolNoticeID` → `ToolID` | - |
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

#### WorksOrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`

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

#### PurchaseInfoSelection

- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`

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

#### PalletSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

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

#### WorksOrderSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

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

#### FirstRealTimeSensorExceptionsSelection

- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`

---

#### LastRealTimeSensorExceptionsSelection

- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`

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

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

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

#### PickRequestSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

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

#### ShiftSummaryDetailSelection

- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`

---

#### ShiftSummarySelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### ProductSelection

- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`

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

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### ToolNoticeWorksOrderSelection

- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`

---

#### DeactivatedToolNoticeSelection

- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:11:38Z*
