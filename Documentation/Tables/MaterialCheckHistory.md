---
layout : default
title : MaterialCheckHistory
parent : Tables
---
# MaterialCheckHistory

## Table Information

- **Table ID:** 39
- **UUID:** CD2B15382AF9D24BB806CE53302773A9
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

### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Regrind

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### CheckedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### DateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### CheckComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### RMC1

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### RMC2

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### RMC3

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### FromSharedSource

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

## Indexes

- **Field:** `RMC1` - Kind: regular, Type: 7
- **Field:** `RMC2` - Kind: regular, Type: 7
- **Field:** `ID` (Unique) - Kind: regular, Type: 7
- **Field:** `WorksOrder` - Kind: regular, Type: 7
- **Field:** `RMC3` - Kind: regular, Type: 7
- **Field:** `MaterialID` - Kind: regular, Type: 7

## Many-to-One Relations

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### RMCEntity1

Links to table: [RMC](RMC.md)

- **Source Field:** `RMC1`
- **Destination Field:** `RMCNo_l`
- **State:** 1

### RMCEntity2

Links to table: [RMC](RMC.md)

- **Source Field:** `RMC2`
- **Destination Field:** `RMCNo_l`
- **State:** 1

### RMCEntity3

Links to table: [RMC](RMC.md)

- **Source Field:** `RMC3`
- **Destination Field:** `RMCNo_l`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

## One-to-Many Relations

### ToolsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### Customer_OrderSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### OrderPickRequestSelection

- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`
- **State:** 1

### Customer_OrderSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### WorksOrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`
- **State:** 1

### WorksOrderSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### Stock_MovementSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### CofCSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### CofCSelection

- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`
- **State:** 1

### Finished_StockSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### Product_OptionSelection

- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### Product_OptionSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### NonConformanceSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### SuppliesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** 1

### PurchasesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** 1

### PurchaseInfoSelection

- **Source Field:** `OrderNo_l`
- **This Table Field:** `OrderNo_l`
- **State:** 1

### GaugesSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### GrippersSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### RMCSelection

- **Source Field:** `MaterialID_l`
- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductReturnSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`
- **State:** 1

### ProductReturnWorksOrderSelection

- **Source Field:** `ReturnID_l`
- **This Table Field:** `ReturnID_l`
- **State:** 1

### ProductReturnWorksOrderSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### LanguageTagSelection

- **Source Field:** `Language_ID`
- **This Table Field:** `ID_l`
- **State:** 1

### ProductPackagingSelection

- **Source Field:** `SuppliesID`
- **This Table Field:** `UniqueID_i`
- **State:** 1

### SuppliesSelection

- **Source Field:** `PackagingCat`
- **This Table Field:** `ID`
- **State:** 1

### ToolLogSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### Stock_MovementSelection

- **Source Field:** `To_Location_l`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### PurchaseInfoSelection

- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`
- **State:** 1

### ProductPackagingSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### WheelCalendarSelection

- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductStockTakeSelection

- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductStocktakeSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ConsignmentEntrySelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ApprovalsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### RealTimeSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** 1

### WorkRequestCommentsSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** 1

### BOMSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### PurchaseInfoSelection

- **Source Field:** `NominalCode`
- **This Table Field:** `ID`
- **State:** 1

### CalibrationsSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** 1

### SupplierDocumentationSelection

- **Source Field:** `SupplierID`
- **This Table Field:** `SupplierID_l`
- **State:** 1

### ProductSelection

- **Source Field:** `PalletMethodID`
- **This Table Field:** `ID`
- **State:** 1

### StaffPermissionsSelection

- **Source Field:** `PermissionID`
- **This Table Field:** `ID`
- **State:** 1

### StaffPermissionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### CalibrationProceduresSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** 1

### CalibrationResultsSelection

- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`
- **State:** 1

### Product_OptionSelection

- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`
- **State:** 1

### Finished_StockSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### PalletSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### LinkedBoxLabelsSelection

- **Source Field:** `LinkedBoxID`
- **This Table Field:** `ID`
- **State:** 1

### PurchaseReceiptsSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** 1

### RMCSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** 1

### PurchaseReceiptsSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### BoxLabelsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### WorksOrderSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`
- **State:** 1

### ProductSelection

- **Source Field:** `EmojiID`
- **This Table Field:** `ID`
- **State:** 1

### WorkRequestsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolMaintenanceLogSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolMaintenanceLogSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** 1

### MachineMaintenanceLogSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** 1

### MachineMaintenanceRequirementsSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** 1

### DB_VariablesSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### PackingInstructionFilesSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### WorkRequestCommentsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### BoxLabelsSelection

- **Source Field:** `PalletID`
- **This Table Field:** `ID`
- **State:** 1

### FirstRealTimeSensorExceptionsSelection

- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`
- **State:** 1

### LastRealTimeSensorExceptionsSelection

- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`
- **State:** 1

### RealTimeSensorExceptionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### RealTimeMachinesSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** 1

### ToolTemperatureTargetSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolTemperatureTargetSelection

- **Source Field:** `ZoneID`
- **This Table Field:** `ID`
- **State:** 1

### ToolTemperatureTargetSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### PalletSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** 1

### LocationSelection

- **Source Field:** `ParentLocationID`
- **This Table Field:** `ID`
- **State:** 1

### ToolDocumentSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### OrderPickRequestSelection

- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`
- **State:** 1

### WheelCalendarSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ProductMaterialOptionsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### MaterialStockTakeSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### PalletSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** 1

### BoxLabelsSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** 1

### PickRequestSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### BoxLabelsSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** 1

### PalletSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** 1

### CofCSelection

- **Source Field:** `Advice_Note_No`
- **This Table Field:** `Advice_Note_No`
- **State:** 1

### CofCSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### CofCSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`
- **State:** 1

### PickRequestSelection

- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`
- **State:** 1

### Customer_OrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`
- **State:** 1

### MaterialStockSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialStockSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** 1

### PrintJobSelection

- **Source Field:** `PrinterID`
- **This Table Field:** `ID`
- **State:** 1

### PrintJobSelection

- **Source Field:** `RelatedUUID`
- **This Table Field:** `UUID`
- **State:** 1

### PrintJobSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### PlanningWheelSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### BoxLabelsSelection

- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### ShiftSummaryDetailSelection

- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`
- **State:** 1

### ShiftSummarySelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### ProductSelection

- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### StatusUpdatedBoxLabelsSelection

- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### ErrorDetailSelection

- **Source Field:** `ErrorID`
- **This Table Field:** `ID`
- **State:** 1

### Customer_OrderSelection

- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`
- **State:** 1

### ForecastSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### CustomerSelection

- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### ToolsSelection

- **Source Field:** `HotHalfID`
- **This Table Field:** `ID`
- **State:** 1

### UsageMat1Selection

- **Source Field:** `UsageMatID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### UsageMat2Selection

- **Source Field:** `UsageMatID2`
- **This Table Field:** `Unique_ID`
- **State:** 1

### UsageMat3Selection

- **Source Field:** `UsageMatID3`
- **This Table Field:** `Unique_ID`
- **State:** 1

### QualitySystemProceduresSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ApprovalsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### BOMSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### Product_OptionSelection

- **Source Field:** `Tool ID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### CustomerContactsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### CustomerSelection

- **Source Field:** `TransportInstructionFileID`
- **This Table Field:** `ID`
- **State:** 1

### ProductPackagingSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### ToolNoticeSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolNoticeSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### ToolNoticeWorksOrderSelection

- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`
- **State:** 1

### DeactivatedToolNoticeSelection

- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`
- **State:** 1

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:10:46Z*
