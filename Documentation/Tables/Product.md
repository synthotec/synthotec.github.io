---
layout : default
title : Product
parent : Tables
---
# Product

## Table Information

- **Table ID:** 10
- **UUID:** C860B832DC3A2742AC90F8A95BC2F157
- **Primary Key:** `Product_ID`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** Primary Key, Unique, Auto-sequence

---

### Our Part No

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** Mandatory, Never Null

---

### Cust Part No

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** Mandatory, Never Null

---

### Issue No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Mandatory, Never Null

---

### Issue Date

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Part Name

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** Mandatory, Never Null

---

### Short Name

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Mandatory, Never Null

---

### Conditioned

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### QuotedCycle

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null, Not Modifiable

---

### DefMatID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Price Quan

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### NoInBox

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Min Order Quan

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### NumOfSquirts

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Drawing No

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Never Null

---

### Regrnd allwd pc

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Odette_PO

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### Packed_Per_Hour

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Programme_No

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Never Null

---

### Tolerance_Low

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Tolerance_High

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### TimePerPallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### MBType

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### MBAmount

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### EmojiID

**Properties:**

- **Type:** Date

---

### Archive

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Inspection Issue

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Inspection IssueDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Inspection IssuedBy

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Inspect Method1

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Inspect Method2

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Inspect Method3

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Inspect Method4

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Inspect Method5

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Patrol Inspect1

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Patrol Inspect2

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Patrol Inspect3

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Patrol Inspect4

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Conversion_Figure

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** Never Null

---

### Quality_FormNo

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Quality_IssueDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Quality_Issuedby

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** Never Null

---

### Quality_ReferenceNo

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** Never Null

---

### Initial_Customer

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Never Null

---

### OperatorRequired

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Inspect_Freq_qty

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Inspect_freq_cycle

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Inspect_freq_period

**Properties:**

- **Type:** String (max length: 9)
- **Constraints:** Never Null

---

### Extra_Text

**Properties:**

- **Type:** String (max length: 40)
- **Constraints:** Never Null

---

### Box_Per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Top_Up_No

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Cond_Cycl_Lght

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Part_No_Colour

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Part_Colour

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Reason_4_Issue_Change

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Danzas_ID

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Cages_per_Mandrell

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Boxes_per_M_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Pallet_Type_m

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Never Null

---

### OurMinimum

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Robot_Prg_No

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### Pallet_Pic

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Production_Mandrell

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Mandrells_per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Mandrel_OD

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### OurBatchSize

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### PrimaryRoute

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Setup_Sheet

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Danzas_ID1

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Danzas_ID2

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### ControlPlanLink1_txt

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### ControlPlanLink2_txt

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Water_Squirt_prog_number

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### RunsPerForecast

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### StockTowardsForecast

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### ForecastQty

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### ForecastOutstanding

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### CoveredByWheel

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### MagicNumber

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Field_80

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### RoutedElsewhere

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### ConsignmentOrder

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### HoursOverride

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Inspect_Freq_MIN

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### PlannedRoute

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### SecondCode

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### UsedSinceBill

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### WareHouseMethod

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### PrioritizeStandardOrders

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### TotalPackTime

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### TotalPackInstances

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### TotalPackString

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### SecondLocation

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### BottomPackTimeTarget

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### BottomPackTimeOverride

**Properties:**

- **Type:** Long Integer
- **Constraints:** Never Null

---

### PalletMethodID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### ClosedLoopPercent

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### ForecastOutstandingCurrentYear

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### AverageRunLength

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### SubContainerQty

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### SubContainerName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### PackingInstructionsFileBlob

**Properties:**

- **Type:** Unknown (18)

---

### PackingInstructionsFileName

**Properties:**

- **Type:** String (max length: 255)

---

### MigrationID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

## Indexes

- **Field:** `MigrationID` - Kind: regular
- **Field:** `PrimaryRoute` - Kind: regular
- **Field:** `Product_ID` (Unique) - Kind: regular
- **Field:** `DefMatID` - Kind: regular
- **Field:** `Cust Part No` - Kind: regular
- **Field:** `EmojiID` - Kind: regular
- **Field:** `Our Part No` - Kind: regular

## Many-to-One Relations

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`

### PalletMethodsEntity

Links to table: [PalletMethods](PalletMethods.md)

- **Source Field:** `PalletMethodID`
- **Destination Field:** `ID`

### EmojisEntity

Links to table: [Emojis](Emojis.md)

- **Source Field:** `EmojiID`
- **Destination Field:** `ID`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `DefMatID`
- **Destination Field:** `Unique_ID`

## One-to-Many Relations

### ToolsSelection

- **Source Field:** `ProductID`
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

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

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

### PrintJobSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

### PlanningWheelSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

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
*Generated at: 2025-11-12T23:08:52Z*
