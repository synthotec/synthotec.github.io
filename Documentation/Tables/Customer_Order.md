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

- **Field:** `Petes_No` (Unique) - Kind: regular, Type: 7
- **Field:** `Reviewed` - Kind: regular, Type: 7
- **Field:** `Forecast` - Kind: regular, Type: 7
- **Field:** `Product_ID` - Kind: regular, Type: 7
- **Field:** `Completed` - Kind: regular, Type: 7
- **Field:** `Our_Delivery_Date` - Kind: regular, Type: 7
- **Field:** `Confirmed` - Kind: regular, Type: 7
- **Field:** `Part_No` - Kind: regular, Type: 7
- **Field:** `ProcurementProgramOrder` - Kind: regular, Type: 7
- **Field:** `Customer_Delivery_Date` - Kind: regular, Type: 7
- **Field:** `Material_ID` - Kind: regular, Type: 7
- **Field:** `FinWheelID` - Kind: regular, Type: 7
- **Field:** `Product_OptionID` - Kind: regular, Type: 7
- **Field:** `Customer_Order_No` - Kind: regular, Type: 7
- **Field:** `FutureYearForecast` - Kind: regular, Type: 7
- **Field:** `Ready_To_Delete` - Kind: regular, Type: 7
- **Field:** `MakeOrder` - Kind: regular, Type: 7
- **Field:** `Customer_Code` - Kind: regular, Type: 7
- **Field:** `Ammeded_Date` - Kind: regular, Type: 7

## Many-to-One Relations

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `Material_ID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** 1

### MaterialEntity

Links to table: [Material](Material.md)

- **Source Field:** `Material_ID`
- **Destination Field:** `Unique_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `Product_ID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** 1

### Product_OptionEntity

Links to table: [Product_Option](Product_Option.md)

- **Source Field:** `Product_OptionID`
- **Destination Field:** `ID`
- **State:** 1

## One-to-Many Relations

### ToolsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### OrderPickRequestSelection

- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`
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

### ApprovalsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
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
*Generated at: 2025-11-12T23:08:45Z*
