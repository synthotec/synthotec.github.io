---
layout : default
title : WorksOrder
parent : Tables
---
# WorksOrder

## Table Information

- **Table ID:** 4
- **UUID:** 305DC4E1E3339443B76C086981BBCB7C
- **Primary Key:** `Works_Order_No`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### Works_Order_No

**Properties:**

- **Type:** Date
- **Constraints:** Primary Key, Unique, Auto-sequence, Mandatory, Never Null

---

### Part_No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Mandatory, Never Null

---

### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Mandatory, Never Null

---

### Production_Target

**Properties:**

- **Type:** Date
- **Constraints:** Mandatory, Never Null

---

### Parts_Packed

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Raised_Job_Card

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Machine_Completed

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### RouteCards

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Notes

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Labels

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### SequencedNo

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### Quantity_Manufactured

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Tool_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Never Null

---

### No_In_Stock

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### MaterialName

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Mandatory, Never Null

---

### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** Mandatory, Never Null

---

### Issue_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Never Null

---

### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Packing_Completed

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Calculated_Scrap

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Label_Text

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### RMC_Nos

**Properties:**

- **Type:** String (max length: 61)
- **Constraints:** Never Null

---

### Machine_No

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Completed_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Packing_Box_No

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Machine_Started

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### WorkInProgress

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Current_Production_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### UpdatePartsMadeDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Is_a_Trial

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Parts_Delivered

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Date_Created

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Quarantine_Finished_Stock

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### DrawingNo

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Never Null

---

### Start_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### PackingSheetPrinted

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Cycle_Time

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Entered_Parts_Scrap

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Fin_Initals

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Part_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Runner_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Weight_Initals

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Dry_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Fin_Packed_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Production_Chart_Status

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Production_Chart_DateSent

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Quarantined_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Quarantine_UnpackedWIP_Stock

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### ReturnsScrap_l

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Quarantine_Returned_Stock_l

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Barcodenum_Part

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodepicture_part

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodenum_quantity

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodepicture_quantity

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodenum_supplierid

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodepicture_supplierid

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodenum_labelid

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodepicture_labelid

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodepicture_workorder

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Barcodenum_worksorder

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Cycle_Flag

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### AmberQuarantine

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### StartTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** Never Null

---

### FinishTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** Never Null

---

### rFtime

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### rStime

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### SetDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### FirstOffCompleted

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### FirstOffComments

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Impressions

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### NewSystem

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### AutomaticStock

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Robot

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### QuarantineReason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### FirstOffWeightsChecked

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### PlannedMaterialID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Regrind

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### MaterialCheckedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### MaterialCheckComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### OEEgenerated

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### LastProcessedRealTimeID

**Properties:**

- **Type:** Date

---

### FixedDate

**Properties:**

- **Type:** Integer

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

- **Field : **  //OEEgenerated` - Kind: regular
OEEgenerated  // - Kind: regular, Type: 7
- **Field : **  //Raised_Job_Card` - Kind: regular
Raised_Job_Card  // - Kind: regular, Type: 7
- **Field : **  //Machine_Started` - Kind: regular
Machine_Started  // - Kind: regular, Type: 7
- **Field : **  //MaterialID` - Kind: regular
MaterialID  // - Kind: regular, Type: 7
- **Field : **  //No_In_Stock` - Kind: regular
No_In_Stock  // - Kind: regular, Type: 7
- **Field : **  //NewSystem` - Kind: regular
NewSystem  // - Kind: regular, Type: 3
- **Field : **  //Machine_No` - Kind: regular
Machine_No  // - Kind: regular, Type: 7
- **Field : **  //Part_No` - Kind: regular
Part_No  // - Kind: regular, Type: 7
- **Field : **  //Customer_Code` - Kind: regular
Customer_Code  // - Kind: regular, Type: 7
- **Field : **  //Works_Order_No` (Unique) - Kind: regular
Works_Order_No  // (Unique) - Kind: regular, Type: 7
- **Field : **  //ToolID` - Kind: regular
ToolID  // - Kind: regular, Type: 7
- **Field : **  //Issue_No` - Kind: regular
Issue_No  // - Kind: regular, Type: 7
- **Field : **  //Machine_Completed` - Kind: regular
Machine_Completed  // - Kind: regular, Type: 7
- **Field : **  //ProductID_l` - Kind: regular
ProductID_l  // - Kind: regular, Type: 7
- **Field : **  //Packing_Completed` - Kind: regular
Packing_Completed  // - Kind: regular, Type: 7
- **Field : **  //Robot` - Kind: regular
Robot  // - Kind: regular, Type: 3
- **Field : **  //MigrationID` - Kind: regular
MigrationID  // - Kind: regular, Type: 7
- **Field : **  //AutomaticStock` - Kind: regular
AutomaticStock  // - Kind: regular, Type: 3

## Many-to-One Relations

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`

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

### Stock_MovementSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

### CofCSelection

- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`

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

### PurchaseInfoSelection

- **Source Field:** `NominalCode`
- **This Table Field:** `ID`

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

### StaffPermissionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

### CalibrationProceduresSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`

### CalibrationResultsSelection

- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`

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

### ProductSelection

- **Source Field:** `EmojiID`
- **This Table Field:** `ID`

### ToolMaintenanceLogSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`

### MachineMaintenanceLogSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

### MachineMaintenanceRequirementsSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

### DB_VariablesSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

### PackingInstructionFilesSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### WorkRequestCommentsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

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

### RealTimeSensorExceptionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

### RealTimeMachinesSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`

### ToolTemperatureTargetSelection

- **Source Field:** `ZoneID`
- **This Table Field:** `ID`

### ToolTemperatureTargetSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

### PalletSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`

### LocationSelection

- **Source Field:** `ParentLocationID`
- **This Table Field:** `ID`

### OrderPickRequestSelection

- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`

### WheelCalendarSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

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

### PickRequestSelection

- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`

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

### PrintJobSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

### BoxLabelsSelection

- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`

### ShiftSummaryDetailSelection

- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`

### ShiftSummarySelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

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

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

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
*Generated at: 2025-11-12T23:08:46Z*
