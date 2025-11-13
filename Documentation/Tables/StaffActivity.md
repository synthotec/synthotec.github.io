---
layout : default
title : StaffActivity
parent : Tables
---
# StaffActivity

## Table Information

- **Table ID:** 75
- **UUID:** D37308D78941F644A7EC6CAE21724BD1
- **Primary Key:** `ID`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### ID

**Properties:**

- **Type:** Date
- **Constraints:** Primary Key, Unique, Auto-sequence

---

### StaffName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### DateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### StaffID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

## Indexes

- **Field:** `ID` (Unique) - Kind: regular

## Many-to-One Relations

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

### StaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`

## One-to-Many Relations

### ToolsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### Customer_OrderSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

### OrderPickRequestSelection

- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`

### Customer_OrderSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`

### WorksOrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`

### WorksOrderSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### Stock_MovementSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

### CofCSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`

### CofCSelection

- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`

### Finished_StockSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`

### Product_OptionSelection

- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`

### Product_OptionSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`

### NonConformanceSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`

### SuppliesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`

### PurchasesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`

### PurchaseInfoSelection

- **Source Field:** `OrderNo_l`
- **This Table Field:** `OrderNo_l`

### GaugesSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

### GrippersSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

### RMCSelection

- **Source Field:** `MaterialID_l`
- **This Table Field:** `Unique_ID`

### ProductReturnSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

### ProductReturnWorksOrderSelection

- **Source Field:** `ReturnID_l`
- **This Table Field:** `ReturnID_l`

### ProductReturnWorksOrderSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

### LanguageTagSelection

- **Source Field:** `Language_ID`
- **This Table Field:** `ID_l`

### BoxLabelsSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### ProductPackagingSelection

- **Source Field:** `SuppliesID`
- **This Table Field:** `UniqueID_i`

### SuppliesSelection

- **Source Field:** `PackagingCat`
- **This Table Field:** `ID`

### ToolLogSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`

### Stock_MovementSelection

- **Source Field:** `To_Location_l`
- **This Table Field:** `StockLocationID_l`

### MaterialCheckHistorySelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### PurchaseInfoSelection

- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`

### RealTimeSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### ProductPackagingSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### WheelCalendarSelection

- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`

### ProductStockTakeSelection

- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`

### ProductStocktakeSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### ConsignmentEntrySelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### ScrapSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### ApprovalsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### RTSUMSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### RealTimeSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`

### WorkRequestCommentsSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`

### BOMSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### BOMSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

### PurchaseInfoSelection

- **Source Field:** `NominalCode`
- **This Table Field:** `ID`

### MaterialCheckHistorySelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

### CalibrationsSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`

### SupplierDocumentationSelection

- **Source Field:** `SupplierID`
- **This Table Field:** `SupplierID_l`

### ProductSelection

- **Source Field:** `PalletMethodID`
- **This Table Field:** `ID`

### StaffPermissionsSelection

- **Source Field:** `PermissionID`
- **This Table Field:** `ID`

### CalibrationProceduresSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`

### CalibrationResultsSelection

- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`

### PlanningWheelSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

### Product_OptionSelection

- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`

### Finished_StockSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`

### PalletSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### LinkedBoxLabelsSelection

- **Source Field:** `LinkedBoxID`
- **This Table Field:** `ID`

### PurchaseReceiptsSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`

### RMCSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`

### PurchaseReceiptsSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

### BoxLabelsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### WorksOrderSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

### ProductSelection

- **Source Field:** `EmojiID`
- **This Table Field:** `ID`

### WorkRequestsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### ToolMaintenanceLogSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### ToolMaintenanceLogSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`

### MachineMaintenanceLogSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

### MachineMaintenanceRequirementsSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

### PackingInstructionFilesSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### BoxLabelsSelection

- **Source Field:** `PalletID`
- **This Table Field:** `ID`

### FirstRealTimeSensorExceptionsSelection

- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`

### LastRealTimeSensorExceptionsSelection

- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`

### RealTimeSensorExceptionsSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### RealTimeMachinesSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`

### ToolTemperatureTargetSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### ToolTemperatureTargetSelection

- **Source Field:** `ZoneID`
- **This Table Field:** `ID`

### PalletSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`

### LocationSelection

- **Source Field:** `ParentLocationID`
- **This Table Field:** `ID`

### ToolDocumentSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### OrderPickRequestSelection

- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`

### WheelCalendarSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### ProductMaterialOptionsSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

### ProductMaterialOptionsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### MaterialStockTakeSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

### MaterialCheckHistorySelection1

- **Source Field:** `RMC1`
- **This Table Field:** `RMCNo_l`

### MaterialCheckHistorySelection2

- **Source Field:** `RMC2`
- **This Table Field:** `RMCNo_l`

### MaterialCheckHistorySelection3

- **Source Field:** `RMC3`
- **This Table Field:** `RMCNo_l`

### PalletSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`

### BoxLabelsSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`

### PickRequestSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

### BoxLabelsSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`

### PalletSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`

### CofCSelection

- **Source Field:** `Advice_Note_No`
- **This Table Field:** `Advice_Note_No`

### CofCSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`

### CofCSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

### PickRequestSelection

- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`

### Customer_OrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`

### MaterialStockSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

### MaterialStockSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

### MaterialStockSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`

### WheelCalendarSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### PrintJobSelection

- **Source Field:** `PrinterID`
- **This Table Field:** `ID`

### PrintJobSelection

- **Source Field:** `RelatedUUID`
- **This Table Field:** `UUID`

### PlanningWheelSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### BoxLabelsSelection

- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`

### ShiftSummaryDetailSelection

- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`

### ShiftSummaryDetailSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### ProductSelection

- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`

### StatusUpdatedBoxLabelsSelection

- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`

### ErrorDetailSelection

- **Source Field:** `ErrorID`
- **This Table Field:** `ID`

### Customer_OrderSelection

- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`

### ForecastSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### CustomerSelection

- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`

### ToolsSelection

- **Source Field:** `HotHalfID`
- **This Table Field:** `ID`

### UsageMat1Selection

- **Source Field:** `UsageMatID`
- **This Table Field:** `Unique_ID`

### UsageMat2Selection

- **Source Field:** `UsageMatID2`
- **This Table Field:** `Unique_ID`

### UsageMat3Selection

- **Source Field:** `UsageMatID3`
- **This Table Field:** `Unique_ID`

### QualitySystemProceduresSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### ApprovalsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

### BOMSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

### WorksOrderSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

### Product_OptionSelection

- **Source Field:** `Tool ID`
- **This Table Field:** `Tool_ID`

### CustomerContactsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

### CustomerSelection

- **Source Field:** `TransportInstructionFileID`
- **This Table Field:** `ID`

### ProductPackagingSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

### ToolNoticeSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

### ToolNoticeWorksOrderSelection

- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`

### ToolNoticeWorksOrderSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

### DeactivatedToolNoticeSelection

- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:11:37Z*
