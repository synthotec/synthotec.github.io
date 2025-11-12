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

- **Field:** `OEEgenerated` - Kind: regular, Type: 7
- **Field:** `Raised_Job_Card` - Kind: regular, Type: 7
- **Field:** `Machine_Started` - Kind: regular, Type: 7
- **Field:** `MaterialID` - Kind: regular, Type: 7
- **Field:** `No_In_Stock` - Kind: regular, Type: 7
- **Field:** `NewSystem` - Kind: regular, Type: 3
- **Field:** `Machine_No` - Kind: regular, Type: 7
- **Field:** `Part_No` - Kind: regular, Type: 7
- **Field:** `Customer_Code` - Kind: regular, Type: 7
- **Field:** `Works_Order_No` (Unique) - Kind: regular, Type: 7
- **Field:** `ToolID` - Kind: regular, Type: 7
- **Field:** `Issue_No` - Kind: regular, Type: 7
- **Field:** `Machine_Completed` - Kind: regular, Type: 7
- **Field:** `ProductID_l` - Kind: regular, Type: 7
- **Field:** `Packing_Completed` - Kind: regular, Type: 7
- **Field:** `Robot` - Kind: regular, Type: 3
- **Field:** `MigrationID` - Kind: regular, Type: 7
- **Field:** `AutomaticStock` - Kind: regular, Type: 3

## Many-to-One Relations

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
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

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
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

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** 1

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
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

### Stock_MovementSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### CofCSelection

- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`
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

### BoxLabelsSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
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

### MaterialCheckHistorySelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### PurchaseInfoSelection

- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`
- **State:** 1

### RealTimeSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
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

### ScrapSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### RTSUMSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
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

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
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

### PickRequestSelection

- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`
- **State:** 1

### MaterialStockSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialStockSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** 1

### WheelCalendarSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
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

### ShiftSummaryDetailSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
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

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### ToolNoticeWorksOrderSelection

- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`
- **State:** 1

### ToolNoticeWorksOrderSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### DeactivatedToolNoticeSelection

- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`
- **State:** 1

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:08:46Z*
