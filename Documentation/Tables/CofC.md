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

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### Customer_OrderSelection

Links from table with field: `Product_ID`

- **This Table Field:** `Product_ID`
- **State:** 1

### OrderPickRequestSelection

Links from table with field: `PickRequestID`

- **This Table Field:** `ID`
- **State:** 1

### Customer_OrderSelection

Links from table with field: `Material_ID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### WorksOrderSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### Stock_MovementSelection

Links from table with field: `Works_Order_No_l`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### Product_OptionSelection

Links from table with field: `Product ID`

- **This Table Field:** `Product_ID`
- **State:** 1

### Product_OptionSelection

Links from table with field: `Material_ID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### NonConformanceSelection

Links from table with field: `Tool_ID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### SuppliesSelection

Links from table with field: `SupplierID_l`

- **This Table Field:** `SupplierID_l`
- **State:** 1

### PurchasesSelection

Links from table with field: `SupplierID_l`

- **This Table Field:** `SupplierID_l`
- **State:** 1

### PurchaseInfoSelection

Links from table with field: `OrderNo_l`

- **This Table Field:** `OrderNo_l`
- **State:** 1

### GaugesSelection

Links from table with field: `Product_ID`

- **This Table Field:** `Product_ID`
- **State:** 1

### GrippersSelection

Links from table with field: `Product_ID`

- **This Table Field:** `Product_ID`
- **State:** 1

### RMCSelection

Links from table with field: `MaterialID_l`

- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductReturnWorksOrderSelection

Links from table with field: `ReturnID_l`

- **This Table Field:** `ReturnID_l`
- **State:** 1

### ProductReturnWorksOrderSelection

Links from table with field: `Works_Order_No_l`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### LanguageTagSelection

Links from table with field: `Language_ID`

- **This Table Field:** `ID_l`
- **State:** 1

### BoxLabelsSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductPackagingSelection

Links from table with field: `SuppliesID`

- **This Table Field:** `UniqueID_i`
- **State:** 1

### SuppliesSelection

Links from table with field: `PackagingCat`

- **This Table Field:** `ID`
- **State:** 1

### ToolLogSelection

Links from table with field: `Tool_ID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### Stock_MovementSelection

Links from table with field: `To_Location_l`

- **This Table Field:** `StockLocationID_l`
- **State:** 1

### MaterialCheckHistorySelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### PurchaseInfoSelection

Links from table with field: `SuppliesID_i`

- **This Table Field:** `UniqueID_i`
- **State:** 1

### RealTimeSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductPackagingSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### WheelCalendarSelection

Links from table with field: `MatID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductStockTakeSelection

Links from table with field: `WO`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductStocktakeSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### ConsignmentEntrySelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### ScrapSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### ApprovalsSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### RTSUMSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### RealTimeSelection

Links from table with field: `DownReason`

- **This Table Field:** `ID`
- **State:** 1

### WorkRequestCommentsSelection

Links from table with field: `WorkRequestID`

- **This Table Field:** `ID`
- **State:** 1

### BOMSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### BOMSelection

Links from table with field: `MaterialID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### PurchaseInfoSelection

Links from table with field: `NominalCode`

- **This Table Field:** `ID`
- **State:** 1

### MaterialCheckHistorySelection

Links from table with field: `MaterialID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### CalibrationsSelection

Links from table with field: `EquipmentID`

- **This Table Field:** `ID`
- **State:** 1

### SupplierDocumentationSelection

Links from table with field: `SupplierID`

- **This Table Field:** `SupplierID_l`
- **State:** 1

### ProductSelection

Links from table with field: `PalletMethodID`

- **This Table Field:** `ID`
- **State:** 1

### StaffPermissionsSelection

Links from table with field: `PermissionID`

- **This Table Field:** `ID`
- **State:** 1

### StaffPermissionsSelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### CalibrationProceduresSelection

Links from table with field: `EquipmentID`

- **This Table Field:** `ID`
- **State:** 1

### CalibrationResultsSelection

Links from table with field: `CalibrationID`

- **This Table Field:** `ID`
- **State:** 1

### PlanningWheelSelection

Links from table with field: `MaterialID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### Product_OptionSelection

Links from table with field: `Customer Code`

- **This Table Field:** `Customer_Code`
- **State:** 1

### PalletSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### LinkedBoxLabelsSelection

Links from table with field: `LinkedBoxID`

- **This Table Field:** `ID`
- **State:** 1

### PurchaseReceiptsSelection

Links from table with field: `PurchaseInfoID`

- **This Table Field:** `UniqueID_l`
- **State:** 1

### RMCSelection

Links from table with field: `PurchaseInfoID`

- **This Table Field:** `UniqueID_l`
- **State:** 1

### PurchaseReceiptsSelection

Links from table with field: `RMC`

- **This Table Field:** `RMCNo_l`
- **State:** 1

### BoxLabelsSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### ProductSelection

Links from table with field: `EmojiID`

- **This Table Field:** `ID`
- **State:** 1

### WorkRequestsSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolMaintenanceLogSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolMaintenanceLogSelection

Links from table with field: `WorkRequestID`

- **This Table Field:** `ID`
- **State:** 1

### MachineMaintenanceLogSelection

Links from table with field: `MachineMaintenanceActionID`

- **This Table Field:** `ID`
- **State:** 1

### MachineMaintenanceRequirementsSelection

Links from table with field: `MachineMaintenanceActionID`

- **This Table Field:** `ID`
- **State:** 1

### DB_VariablesSelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### PackingInstructionFilesSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### WorkRequestCommentsSelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### BoxLabelsSelection

Links from table with field: `PalletID`

- **This Table Field:** `ID`
- **State:** 1

### FirstRealTimeSensorExceptionsSelection

Links from table with field: `FirstRealTimeID`

- **This Table Field:** `ID`
- **State:** 1

### LastRealTimeSensorExceptionsSelection

Links from table with field: `LastRealTimeID`

- **This Table Field:** `ID`
- **State:** 1

### RealTimeSensorExceptionsSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### RealTimeSensorExceptionsSelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### RealTimeMachinesSelection

Links from table with field: `DownReason`

- **This Table Field:** `ID`
- **State:** 1

### ToolTemperatureTargetSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolTemperatureTargetSelection

Links from table with field: `ZoneID`

- **This Table Field:** `ID`
- **State:** 1

### ToolTemperatureTargetSelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### PalletSelection

Links from table with field: `LocationID`

- **This Table Field:** `ID`
- **State:** 1

### LocationSelection

Links from table with field: `ParentLocationID`

- **This Table Field:** `ID`
- **State:** 1

### ToolDocumentSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### OrderPickRequestSelection

Links from table with field: `CustomerOrderID`

- **This Table Field:** `Petes_No`
- **State:** 1

### WheelCalendarSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### ProductMaterialOptionsSelection

Links from table with field: `MaterialID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductMaterialOptionsSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### MaterialStockTakeSelection

Links from table with field: `RMC`

- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection1

Links from table with field: `RMC1`

- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection2

Links from table with field: `RMC2`

- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialCheckHistorySelection3

Links from table with field: `RMC3`

- **This Table Field:** `RMCNo_l`
- **State:** 1

### PalletSelection

Links from table with field: `OrderPickRequestID`

- **This Table Field:** `ID`
- **State:** 1

### BoxLabelsSelection

Links from table with field: `OrderPickRequestID`

- **This Table Field:** `ID`
- **State:** 1

### PickRequestSelection

Links from table with field: `Customer`

- **This Table Field:** `Customer_Code`
- **State:** 1

### BoxLabelsSelection

Links from table with field: `CofCID`

- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** 1

### PalletSelection

Links from table with field: `CofCID`

- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** 1

### PickRequestSelection

Links from table with field: `AdviceNoteID`

- **This Table Field:** `ID`
- **State:** 1

### MaterialStockSelection

Links from table with field: `MaterialID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### MaterialStockSelection

Links from table with field: `RMC`

- **This Table Field:** `RMCNo_l`
- **State:** 1

### MaterialStockSelection

Links from table with field: `LocationID`

- **This Table Field:** `ID`
- **State:** 1

### WheelCalendarSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### PrintJobSelection

Links from table with field: `PrinterID`

- **This Table Field:** `ID`
- **State:** 1

### PrintJobSelection

Links from table with field: `RelatedUUID`

- **This Table Field:** `UUID`
- **State:** 1

### PrintJobSelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### PlanningWheelSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### BoxLabelsSelection

Links from table with field: `Stock_LocationID`

- **This Table Field:** `StockLocationID_l`
- **State:** 1

### ShiftSummaryDetailSelection

Links from table with field: `ShiftSummaryID`

- **This Table Field:** `ID`
- **State:** 1

### ShiftSummarySelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### ShiftSummaryDetailSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### ProductSelection

Links from table with field: `DefMatID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### StatusUpdatedBoxLabelsSelection

Links from table with field: `StatusUpdatedStaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### ErrorDetailSelection

Links from table with field: `ErrorID`

- **This Table Field:** `ID`
- **State:** 1

### Customer_OrderSelection

Links from table with field: `Product_OptionID`

- **This Table Field:** `ID`
- **State:** 1

### ForecastSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### CustomerSelection

Links from table with field: `ConsignmentLocationID`

- **This Table Field:** `StockLocationID_l`
- **State:** 1

### ToolsSelection

Links from table with field: `HotHalfID`

- **This Table Field:** `ID`
- **State:** 1

### UsageMat1Selection

Links from table with field: `UsageMatID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### UsageMat2Selection

Links from table with field: `UsageMatID2`

- **This Table Field:** `Unique_ID`
- **State:** 1

### UsageMat3Selection

Links from table with field: `UsageMatID3`

- **This Table Field:** `Unique_ID`
- **State:** 1

### QualitySystemProceduresSelection

Links from table with field: `ProductID`

- **This Table Field:** `Product_ID`
- **State:** 1

### ApprovalsSelection

Links from table with field: `Customer`

- **This Table Field:** `Customer_Code`
- **State:** 1

### BOMSelection

Links from table with field: `Customer`

- **This Table Field:** `Customer_Code`
- **State:** 1

### WorksOrderSelection

Links from table with field: `MaterialID`

- **This Table Field:** `Unique_ID`
- **State:** 1

### Product_OptionSelection

Links from table with field: `Tool ID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### CustomerContactsSelection

Links from table with field: `Customer`

- **This Table Field:** `Customer_Code`
- **State:** 1

### CustomerSelection

Links from table with field: `TransportInstructionFileID`

- **This Table Field:** `ID`
- **State:** 1

### ProductPackagingSelection

Links from table with field: `Customer`

- **This Table Field:** `Customer_Code`
- **State:** 1

### ToolNoticeSelection

Links from table with field: `ToolID`

- **This Table Field:** `Tool_ID`
- **State:** 1

### ToolNoticeSelection

Links from table with field: `StaffID`

- **This Table Field:** `StaffID`
- **State:** 1

### ToolNoticeWorksOrderSelection

Links from table with field: `ToolNoticeID`

- **This Table Field:** `ToolID`
- **State:** 1

### ToolNoticeWorksOrderSelection

Links from table with field: `WorksOrder`

- **This Table Field:** `Works_Order_No`
- **State:** 1

### DeactivatedToolNoticeSelection

Links from table with field: `DeactivatedStaffID`

- **This Table Field:** `StaffID`
- **State:** 1

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:08:48Z*
