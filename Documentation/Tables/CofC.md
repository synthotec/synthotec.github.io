# CofC

## Table Information

- **Table ID:** 6
- **UUID:** 81B9B2AF685A1B4E892794C866475FCC
- **Primary Key:** `Cert_Of_Conformance_No`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### Cert_Of_Conformance_No

Test

**Properties:**

- **Type:** Date
- **Constraints:** Primary Key, Unique, Auto-sequence, Mandatory, Never Null

---

### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Mandatory, Never Null

---

### Created_Date

**Properties:**

- **Type:** Integer
- **Constraints:** Mandatory, Never Null

---

### Advice_Note_No

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Part No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Mandatory, Never Null

---

### Customer_Order_No

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Mandatory, Never Null

---

### MovementCofC

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### RMC_Nos

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Delivery_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** Mandatory, Never Null

---

### Works_Order_No

**Properties:**

- **Type:** Date
- **Constraints:** Mandatory, Never Null

---

### Petes No

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Quantity_Loose

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Price

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Nunber_Of_Boxes

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Number_In_Box

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### loose

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Order_Completed

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Batch_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Never Null

---

### CofC_Report

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Invoice_Report

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Date_Int

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### DeliveredDate_d

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### LocationID_l

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### LocationName_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Delivery_Method_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

## Indexes

- **Field:** `Cert_Of_Conformance_No` (Unique) - Kind: regular, Type: 7
- **Field:** `CofC_Report` - Kind: regular, Type: 7
- **Field:** `Works_Order_No` - Kind: regular, Type: 7
- **Field:** `Advice_Note_No` - Kind: regular, Type: 7
- **Field:** `Date_Int` - Kind: regular, Type: 7
- **Field:** `Customer_Code` - Kind: regular, Type: 7
- **Field:** `Invoice_Report` - Kind: regular, Type: 7
- **Field:** `ProductID_l` - Kind: regular, Type: 7
- **Field:** `MovementCofC` - Kind: regular, Type: 7
- **Field:** `Part No` - Kind: regular, Type: 7
- **Field:** `Petes No` - Kind: regular, Type: 7

## Many-to-One Relations

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** 1

### WorksOrderEntity

Links to table: [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`
- **State:** 1

### Customer_OrderEntity

Links to table: [Customer_Order](Customer_Order.md)

- **Source Field:** `Petes No`
- **Destination Field:** `Petes_No`
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

### Stock_LocationEntity

Links to table: [Stock_Location](Stock_Location.md)

- **Source Field:** `LocationID_l`
- **Destination Field:** `StockLocationID_l`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** 1

### Advice_NoteEntity

Links to table: [Advice_Note](Advice_Note.md)

- **Source Field:** `Advice_Note_No`
- **Destination Field:** `Advice_Note_No`
- **State:** 1

### Stock_LocationEntity

Links to table: [Stock_Location](Stock_Location.md)

- **Source Field:** `LocationID_l`
- **Destination Field:** `StockLocationID_l`
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

## One-to-Many Relations

### ToolsSelection

Links from table: [Tools](Tools.md)

- **Source Table:** `Tools`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### Customer_OrderSelection

Links from table: [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### OrderPickRequestSelection

Links from table: [OrderPickRequest](OrderPickRequest.md)

- **Source Table:** `OrderPickRequest`
- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`
- **State:** 1

### Customer_OrderSelection

Links from table: [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### WorksOrderSelection

Links from table: [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### Stock_MovementSelection

Links from table: [Stock_Movement](Stock_Movement.md)

- **Source Table:** `Stock_Movement`
- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### Product_OptionSelection

Links from table: [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### Product_OptionSelection

Links from table: [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### NonConformanceSelection

Links from table: [NonConformance](NonConformance.md)

- **Source Table:** `NonConformance`
- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### SuppliesSelection

Links from table: [Supplies](Supplies.md)

- **Source Table:** `Supplies`
- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** 1

### PurchasesSelection

Links from table: [Purchases](Purchases.md)

- **Source Table:** `Purchases`
- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** 1

### PurchaseInfoSelection

Links from table: [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `OrderNo_l`
- **This Table Field:** `OrderNo_l`
- **State:** 1

### GaugesSelection

Links from table: [Gauges](Gauges.md)

- **Source Table:** `Gauges`
- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### GrippersSelection

Links from table: [Grippers](Grippers.md)

- **Source Table:** `Grippers`
- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`
- **State:** 1

### RMCSelection

Links from table: [RMC](RMC.md)

- **Source Table:** `RMC`
- **Source Field:** `MaterialID_l`
- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductReturnWorksOrderSelection

Links from table: [ProductReturnWorksOrder](ProductReturnWorksOrder.md)

- **Source Table:** `ProductReturnWorksOrder`
- **Source Field:** `ReturnID_l`
- **This Table Field:** `ReturnID_l`
- **State:** 1

### ProductReturnWorksOrderSelection

Links from table: [ProductReturnWorksOrder](ProductReturnWorksOrder.md)

- **Source Table:** `ProductReturnWorksOrder`
- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### LanguageTagSelection

Links from table: [LanguageTag](LanguageTag.md)

- **Source Table:** `LanguageTag`
- **Source Field:** `Language_ID`
- **This Table Field:** `ID_l`
- **State:** 1

### BoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductPackagingSelection

Links from table: [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `SuppliesID`
- **This Table Field:** `UniqueID_i`
- **State:** 1

### SuppliesSelection

Links from table: [Supplies](Supplies.md)

- **Source Table:** `Supplies`
- **Source Field:** `PackagingCat`
- **This Table Field:** `ID`
- **State:** 1

### ToolLogSelection

Links from table: [ToolLog](ToolLog.md)

- **Source Table:** `ToolLog`
- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### Stock_MovementSelection

Links from table: [Stock_Movement](Stock_Movement.md)

- **Source Table:** `Stock_Movement`
- **Source Field:** `To_Location_l`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### MaterialCheckHistorySelection

Links from table: [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### PurchaseInfoSelection

Links from table: [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`
- **State:** 1

### RealTimeSelection

Links from table: [RealTime](RealTime.md)

- **Source Table:** `RealTime`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductPackagingSelection

Links from table: [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### WheelCalendarSelection

Links from table: [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductStockTakeSelection

Links from table: [ProductStockTake](ProductStockTake.md)

- **Source Table:** `ProductStockTake`
- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductStocktakeSelection

Links from table: [ProductStockTake](ProductStockTake.md)

- **Source Table:** `ProductStockTake`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ConsignmentEntrySelection

Links from table: [ConsignmentEntry](ConsignmentEntry.md)

- **Source Table:** `ConsignmentEntry`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ScrapSelection

Links from table: [Scrap](Scrap.md)

- **Source Table:** `Scrap`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### ApprovalsSelection

Links from table: [Approvals](Approvals.md)

- **Source Table:** `Approvals`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### RTSUMSelection

Links from table: [RTSUM](RTSUM.md)

- **Source Table:** `RTSUM`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### RealTimeSelection

Links from table: [RealTime](RealTime.md)

- **Source Table:** `RealTime`
- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** 1

### WorkRequestCommentsSelection

Links from table: [WorkRequestComments](WorkRequestComments.md)

- **Source Table:** `WorkRequestComments`
- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** 1

### BOMSelection

Links from table: [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### BOMSelection

Links from table: [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### PurchaseInfoSelection

Links from table: [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `NominalCode`
- **This Table Field:** `ID`
- **State:** 1

### MaterialCheckHistorySelection

Links from table: [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### CalibrationsSelection

Links from table: [Calibrations](Calibrations.md)

- **Source Table:** `Calibrations`
- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** 1

### SupplierDocumentationSelection

Links from table: [SupplierDocumentation](SupplierDocumentation.md)

- **Source Table:** `SupplierDocumentation`
- **Source Field:** `SupplierID`
- **This Table Field:** `SupplierID_l`
- **State:** 1

### ProductSelection

Links from table: [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `PalletMethodID`
- **This Table Field:** `ID`
- **State:** 1

### StaffPermissionsSelection

Links from table: [StaffPermissions](StaffPermissions.md)

- **Source Table:** `StaffPermissions`
- **Source Field:** `PermissionID`
- **This Table Field:** `ID`
- **State:** 1

### StaffPermissionsSelection

Links from table: [StaffPermissions](StaffPermissions.md)

- **Source Table:** `StaffPermissions`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### CalibrationProceduresSelection

Links from table: [CalibrationProcedures](CalibrationProcedures.md)

- **Source Table:** `CalibrationProcedures`
- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** 1

### CalibrationResultsSelection

Links from table: [CalibrationResults](CalibrationResults.md)

- **Source Table:** `CalibrationResults`
- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`
- **State:** 1

### PlanningWheelSelection

Links from table: [PlanningWheel](PlanningWheel.md)

- **Source Table:** `PlanningWheel`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### Product_OptionSelection

Links from table: [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`
- **State:** 1

### PalletSelection

Links from table: [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### LinkedBoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `LinkedBoxID`
- **This Table Field:** `ID`
- **State:** 1

### PurchaseReceiptsSelection

Links from table: [PurchaseReceipts](PurchaseReceipts.md)

- **Source Table:** `PurchaseReceipts`
- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** 1

### RMCSelection

Links from table: [RMC](RMC.md)

- **Source Table:** `RMC`
- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** 1

### PurchaseReceiptsSelection

Links from table: [PurchaseReceipts](PurchaseReceipts.md)

- **Source Table:** `PurchaseReceipts`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### BoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ProductSelection

Links from table: [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `EmojiID`
- **This Table Field:** `ID`
- **State:** 1

### WorkRequestsSelection

Links from table: [WorkRequests](WorkRequests.md)

- **Source Table:** `WorkRequests`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolMaintenanceLogSelection

Links from table: [ToolMaintenanceLog](ToolMaintenanceLog.md)

- **Source Table:** `ToolMaintenanceLog`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolMaintenanceLogSelection

Links from table: [ToolMaintenanceLog](ToolMaintenanceLog.md)

- **Source Table:** `ToolMaintenanceLog`
- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** 1

### MachineMaintenanceLogSelection

Links from table: [MachineMaintenanceLog](MachineMaintenanceLog.md)

- **Source Table:** `MachineMaintenanceLog`
- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** 1

### MachineMaintenanceRequirementsSelection

Links from table: [MachineMaintenanceRequirements](MachineMaintenanceRequirements.md)

- **Source Table:** `MachineMaintenanceRequirements`
- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** 1

### DB_VariablesSelection

Links from table: [Settings](Settings.md)

- **Source Table:** `Settings`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### PackingInstructionFilesSelection

Links from table: [PackingInstructionFiles](PackingInstructionFiles.md)

- **Source Table:** `PackingInstructionFiles`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### WorkRequestCommentsSelection

Links from table: [WorkRequestComments](WorkRequestComments.md)

- **Source Table:** `WorkRequestComments`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### BoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `PalletID`
- **This Table Field:** `ID`
- **State:** 1

### FirstRealTimeSensorExceptionsSelection

Links from table: [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`
- **State:** 1

### LastRealTimeSensorExceptionsSelection

Links from table: [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`
- **State:** 1

### RealTimeSensorExceptionsSelection

Links from table: [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### RealTimeSensorExceptionsSelection

Links from table: [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### RealTimeMachinesSelection

Links from table: [RealTimeMachines](RealTimeMachines.md)

- **Source Table:** `RealTimeMachines`
- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** 1

### ToolTemperatureTargetSelection

Links from table: [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolTemperatureTargetSelection

Links from table: [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `ZoneID`
- **This Table Field:** `ID`
- **State:** 1

### ToolTemperatureTargetSelection

Links from table: [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### PalletSelection

Links from table: [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** 1

### LocationSelection

Links from table: [Location](Location.md)

- **Source Table:** `Location`
- **Source Field:** `ParentLocationID`
- **This Table Field:** `ID`
- **State:** 1

### ToolDocumentSelection

Links from table: [ToolDocument](ToolDocument.md)

- **Source Table:** `ToolDocument`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### OrderPickRequestSelection

Links from table: [OrderPickRequest](OrderPickRequest.md)

- **Source Table:** `OrderPickRequest`
- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`
- **State:** 1

### WheelCalendarSelection

Links from table: [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ProductMaterialOptionsSelection

Links from table: [ProductMaterialOptions](ProductMaterialOptions.md)

- **Source Table:** `ProductMaterialOptions`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductMaterialOptionsSelection

Links from table: [ProductMaterialOptions](ProductMaterialOptions.md)

- **Source Table:** `ProductMaterialOptions`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### MaterialStockTakeSelection

Links from table: [MaterialStockTake](MaterialStockTake.md)

- **Source Table:** `MaterialStockTake`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection1

> Relationship comment test

Links from table: [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC1`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection2

Links from table: [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC2`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection3

Links from table: [MaterialCheckHistory](MaterialCheckHistory.md)

- **Source Table:** `MaterialCheckHistory`
- **Source Field:** `RMC3`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### PalletSelection

Links from table: [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** 1

### BoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** 1

### PickRequestSelection

Links from table: [PickRequest](PickRequest.md)

- **Source Table:** `PickRequest`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### BoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** 1

### PalletSelection

Links from table: [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** 1

### PickRequestSelection

Links from table: [PickRequest](PickRequest.md)

- **Source Table:** `PickRequest`
- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`
- **State:** 1

### MaterialStockSelection

Links from table: [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### MaterialStockSelection

Links from table: [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialStockSelection

Links from table: [MaterialStock](MaterialStock.md)

- **Source Table:** `MaterialStock`
- **Source Field:** `LocationID`
- **This Table Field:** `ID`
- **State:** 1

### WheelCalendarSelection

Links from table: [WheelCalendar](WheelCalendar.md)

- **Source Table:** `WheelCalendar`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### PrintJobSelection

Links from table: [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `PrinterID`
- **This Table Field:** `ID`
- **State:** 1

### PrintJobSelection

Links from table: [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `RelatedUUID`
- **This Table Field:** `UUID`
- **State:** 1

### PrintJobSelection

Links from table: [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### PlanningWheelSelection

Links from table: [PlanningWheel](PlanningWheel.md)

- **Source Table:** `PlanningWheel`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### BoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### ShiftSummaryDetailSelection

Links from table: [ShiftSummaryDetail](ShiftSummaryDetail.md)

- **Source Table:** `ShiftSummaryDetail`
- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`
- **State:** 1

### ShiftSummarySelection

Links from table: [ShiftSummary](ShiftSummary.md)

- **Source Table:** `ShiftSummary`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### ShiftSummaryDetailSelection

Links from table: [ShiftSummaryDetail](ShiftSummaryDetail.md)

- **Source Table:** `ShiftSummaryDetail`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductSelection

Links from table: [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### StatusUpdatedBoxLabelsSelection

Links from table: [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### ErrorDetailSelection

Links from table: [ErrorDetail](ErrorDetail.md)

- **Source Table:** `ErrorDetail`
- **Source Field:** `ErrorID`
- **This Table Field:** `ID`
- **State:** 1

### Customer_OrderSelection

Links from table: [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`
- **State:** 1

### ForecastSelection

Links from table: [Forecast](Forecast.md)

- **Source Table:** `Forecast`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### CustomerSelection

Links from table: [Customer](Customer.md)

- **Source Table:** `Customer`
- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** 1

### ToolsSelection

Links from table: [Tools](Tools.md)

- **Source Table:** `Tools`
- **Source Field:** `HotHalfID`
- **This Table Field:** `ID`
- **State:** 1

### UsageMat1Selection

Links from table: [Material](Material.md)

- **Source Table:** `Material`
- **Source Field:** `UsageMatID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### UsageMat2Selection

Links from table: [Material](Material.md)

- **Source Table:** `Material`
- **Source Field:** `UsageMatID2`
- **This Table Field:** `Unique_ID`
- **State:** 1

### UsageMat3Selection

Links from table: [Material](Material.md)

- **Source Table:** `Material`
- **Source Field:** `UsageMatID3`
- **This Table Field:** `Unique_ID`
- **State:** 1

### QualitySystemProceduresSelection

Links from table: [QualitySystemProcedures](QualitySystemProcedures.md)

- **Source Table:** `QualitySystemProcedures`
- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
- **State:** 1

### ApprovalsSelection

Links from table: [Approvals](Approvals.md)

- **Source Table:** `Approvals`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### BOMSelection

Links from table: [BOM](BOM.md)

- **Source Table:** `BOM`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### WorksOrderSelection

Links from table: [WorksOrder](WorksOrder.md)

- **Source Table:** `WorksOrder`
- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### Product_OptionSelection

Links from table: [Product_Option](Product_Option.md)

- **Source Table:** `Product_Option`
- **Source Field:** `Tool ID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### CustomerContactsSelection

Links from table: [CustomerContacts](CustomerContacts.md)

- **Source Table:** `CustomerContacts`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### CustomerSelection

Links from table: [Customer](Customer.md)

- **Source Table:** `Customer`
- **Source Field:** `TransportInstructionFileID`
- **This Table Field:** `ID`
- **State:** 1

### ProductPackagingSelection

Links from table: [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`
- **State:** 1

### ToolNoticeSelection

Links from table: [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolNoticeSelection

Links from table: [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** 1

### ToolNoticeWorksOrderSelection

Links from table: [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md)

- **Source Table:** `ToolNoticeWorksOrder`
- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`
- **State:** 1

### ToolNoticeWorksOrderSelection

Links from table: [ToolNoticeWorksOrder](ToolNoticeWorksOrder.md)

- **Source Table:** `ToolNoticeWorksOrder`
- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`
- **State:** 1

### DeactivatedToolNoticeSelection

Links from table: [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`
- **State:** 1

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:41:13Z*
