---
layout : default
title : Customer_Order
parent : Tables
---
# Customer_Order

## Table Information

- **Table ID:** 3
- **UUID:** BEB2206FADBF794D8690FF16FF7721B1
- **Primary Key:** `Petes_No`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Issue_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Mandatory, Never Null

---

### Date_Received

**Properties:**

- **Type:** Integer
- **Constraints:** Mandatory, Never Null

---

### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Mandatory, Never Null

---

### Customer_Order_No

**Properties:**

- **Type:** String (max length: 18)
- **Constraints:** Mandatory, Never Null

---

### Customer_Order_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Mandatory, Never Null

---

### Part_No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Mandatory, Never Null

---

### Issue_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Mandatory, Never Null

---

### Quantity_Ordered

**Properties:**

- **Type:** Date
- **Constraints:** Mandatory, Never Null

---

### Batch_No

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Customer_Delivery_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Mandatory, Never Null

---

### Our_Delivery_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Mandatory, Never Null

---

### Price_Quantity

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Order_Price

**Properties:**

- **Type:** Boolean
- **Constraints:** Mandatory, Never Null

---

### Is_Replacement

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Tool_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Never Null

---

### Nominal_Sale

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Material_ID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Material_CName

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### Tool_ID

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### MaterialOurName

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### Cust Part No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null, Hidden

---

### Quantity_Delivered

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Cumulative

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Suggested

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Is_On_hold

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Completed

**Properties:**

- **Type:** Real
- **Constraints:** Mandatory, Never Null

---

### Quantity_Required

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Petes_No

**Properties:**

- **Type:** Date
- **Constraints:** Primary Key, Unique, Auto-sequence, Never Null, Not Modifiable

---

### CalculatedDespatchDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Status

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Never Null

---

### Acknowledged

**Properties:**

- **Type:** Real
- **Constraints:** Mandatory, Never Null

---

### Part_Delivery

**Properties:**

- **Type:** Real
- **Constraints:** Mandatory, Never Null

---

### Invoiced

**Properties:**

- **Type:** Real
- **Constraints:** Mandatory, Never Null

---

### Ready_To_Delete

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Is_a_Trial

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Delivered_Value

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Ammeded_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Is_New_Order

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### QtyMonthAfter

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### BoxesMonthAfter

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### OTIF

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### OTIF_Shortfall

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### OTIF_Comments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### ConsignmentOTIFCheck

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### ProductionReadyDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### ReadyOnDate

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### DaysLate

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### OrderNotes

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### MCPlanned

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### NSKDelivered

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### NSKUndelivered

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### NSKCurrentSYNStock

**Properties:**

- **Type:** Undefined
- **Constraints:** Never Null

---

### ConsignmentDummy

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### FinWheelID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### FinWheelMC

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### ConOrderDummy

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Reviewed

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### DateReviewed

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### ReviewedReadyDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Confirmed

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### ConfirmedDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### ConfirmedDue

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### MakeOrder

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### SIMUsageOrder

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Product_OptionID

**Properties:**

- **Type:** Date

---

### ProcurementProgramOrder

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Forecast

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### FutureYearForecast

**Properties:**

- **Type:** Real

---

## Indexes

- **Field:** `Petes_No` (Unique) - Kind: regular
- **Field:** `Reviewed` - Kind: regular
- **Field:** `Forecast` - Kind: regular
- **Field:** `Product_ID` - Kind: regular
- **Field:** `Completed` - Kind: regular
- **Field:** `Our_Delivery_Date` - Kind: regular
- **Field:** `Confirmed` - Kind: regular
- **Field:** `Part_No` - Kind: regular
- **Field:** `ProcurementProgramOrder` - Kind: regular
- **Field:** `Customer_Delivery_Date` - Kind: regular
- **Field:** `Material_ID` - Kind: regular
- **Field:** `FinWheelID` - Kind: regular
- **Field:** `Product_OptionID` - Kind: regular
- **Field:** `Customer_Order_No` - Kind: regular
- **Field:** `FutureYearForecast` - Kind: regular
- **Field:** `Ready_To_Delete` - Kind: regular
- **Field:** `MakeOrder` - Kind: regular
- **Field:** `Customer_Code` - Kind: regular
- **Field:** `Ammeded_Date` - Kind: regular

## Many-to-One Relations

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `Material_ID`
- **Destination Field:** `Unique_ID`

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `Material_ID`
- **Destination Field:** `Unique_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

### Product_OptionEntity

Links to table: [Product_Option](Product_Option.md)

- **Source Field:** `Product_OptionID`
- **Destination Field:** `ID`

## One-to-Many Relations

### ToolsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

### OrderPickRequestSelection

- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`

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

### ProductSelection

- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`

### StatusUpdatedBoxLabelsSelection

- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`

### ErrorDetailSelection

- **Source Field:** `ErrorID`
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
*Generated at: 2025-11-12T23:08:45Z*
