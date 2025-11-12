---
layout : default
title : BoxLabels
parent : Tables
---
# BoxLabels

## Table Information

- **Table ID:** 76
- **UUID:** 0B40C76291EE2E44AC3F733AD8213391
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

### BoxNumber

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### RouteCard

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### PackedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### Date

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Time

**Properties:**

- **Type:** Long Integer
- **Constraints:** Never Null

---

### DateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Parts

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Shift

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### WORC

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Mandrels

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### NotMade

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### NotMadeWho

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### TimeToPack

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### StockInput

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### TimeProcessed

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### StandardHours

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### ShiftDate

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### PartBoxCode

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Never Null

---

### LinkedBoxID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### RemoveFromStock

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### StockRemovedBy

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### PalletID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### WhenAddedToPallet

**Properties:**

- **Type:** String (max length: 255)

---

### OrderPickRequestID

**Properties:**

- **Type:** Date

---

### Version

**Properties:**

- **Type:** Picture

---

### CofCID

**Properties:**

- **Type:** Date

---

### Stock_LocationID

**Properties:**

- **Type:** Date

---

### Comments

**Properties:**

- **Type:** String

---

### StatusUpdatedStaffID

**Properties:**

- **Type:** Date

---

### StatusUpdatedWhen

**Properties:**

- **Type:** String (max length: 255)

---

### UUID

**Properties:**

- **Type:** String

---

### MigrationID

**Properties:**

- **Type:** Date

---

### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

## Indexes

- **Field:** `PalletID` - Kind: regular, Type: 7
- **Field:** `WorksOrder` - Kind: regular, Type: 3
- **Field:** `UUID` - Kind: regular, Type: 7
- **Field:** `ToolID` - Kind: regular, Type: 7
- **Field:** `ID` (Unique) - Kind: regular, Type: 7
- **Field:** `Shift` - Kind: regular, Type: 7
- **Field:** `StockRemovedBy` - Kind: regular, Type: 7
- **Field:** `RemoveFromStock` - Kind: regular, Type: 3
- **Field:** `Stock_LocationID` - Kind: regular, Type: 7
- **Field:** `LinkedBoxID` - Kind: regular, Type: 7
- **Field:** `TimeProcessed` - Kind: regular, Type: 7
- **Field:** `PackedBy` - Kind: regular, Type: 7
- **Field:** `CofCID` - Kind: regular, Type: 7
- **Field:** `Version` - Kind: regular, Type: 7
- **Field:** `StockInput` - Kind: regular, Type: 3
- **Field:** `OrderPickRequestID` - Kind: regular, Type: 7
- **Field:** `ShiftDate` - Kind: regular, Type: 7
- **Field:** `PartBoxCode` - Kind: regular, Type: 7
- **Field:** `NotMade` - Kind: regular, Type: 3

## Many-to-One Relations

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
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

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### LinkedBoxLabelsEntity

Links to table: [BoxLabels](BoxLabels.md)

- **Source Field:** `LinkedBoxID`
- **Destination Field:** `ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### PalletEntity

Links to table: [Pallet](Pallet.md)

- **Source Field:** `PalletID`
- **Destination Field:** `ID`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### OrderPickRequestEntity

Links to table: [OrderPickRequest](OrderPickRequest.md)

- **Source Field:** `OrderPickRequestID`
- **Destination Field:** `ID`
- **State:** 1

### OrderPickRequestEntity

Links to table: [OrderPickRequest](OrderPickRequest.md)

- **Source Field:** `OrderPickRequestID`
- **Destination Field:** `ID`
- **State:** 1

### CofCEntity

Links to table: [CofC](CofC.md)

- **Source Field:** `CofCID`
- **Destination Field:** `Cert_Of_Conformance_No`
- **State:** 1

### CofCEntity

Links to table: [CofC](CofC.md)

- **Source Field:** `CofCID`
- **Destination Field:** `Cert_Of_Conformance_No`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### Stock_LocationEntity

Links to table: [Stock_Location](Stock_Location.md)

- **Source Field:** `Stock_LocationID`
- **Destination Field:** `StockLocationID_l`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### StatusUpdatedStaffEntity

Links to table: [Staff](Staff.md)

- **Source Field:** `StatusUpdatedStaffID`
- **Destination Field:** `StaffID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
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

### BOMSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### PurchaseInfoSelection

- **Source Field:** `NominalCode`
- **This Table Field:** `ID`
- **State:** 1

### MaterialCheckHistorySelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
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

### PlanningWheelSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
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

### WorksOrderSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`
- **State:** 1

### ProductSelection

- **Source Field:** `EmojiID`
- **This Table Field:** `ID`
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

### OrderPickRequestSelection

- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`
- **State:** 1

### WheelCalendarSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ProductMaterialOptionsSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductMaterialOptionsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### MaterialStockTakeSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection1

- **Source Field:** `RMC1`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection2

- **Source Field:** `RMC2`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection3

- **Source Field:** `RMC3`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### PickRequestSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
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

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
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

### WorksOrderSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
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
*Generated at: 2025-11-12T23:11:38Z*
