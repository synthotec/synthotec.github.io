---
layout : default
title : Suppliers
parent : Tables
---
# Suppliers

## Table Information

- **Table ID:** 18
- **UUID:** DD48C27A4EEF9442A7DB4C93B8CD90D3
- **Primary Key:** `SupplierID_l`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### SupplierID_l

**Properties:**

- **Type:** Date
- **Constraints:** Primary Key, Unique, Auto-sequence, Never Null, Not Modifiable

---

### Name_s

**Properties:**

- **Type:** String (max length: 31)
- **Constraints:** Mandatory, Never Null

---

### Address1_s

**Properties:**

- **Type:** String (max length: 41)
- **Constraints:** Never Null

---

### Address2_s

**Properties:**

- **Type:** String (max length: 41)
- **Constraints:** Never Null

---

### Address3_s

**Properties:**

- **Type:** String (max length: 41)
- **Constraints:** Never Null

---

### County_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** Never Null

---

### Postcode_s

**Properties:**

- **Type:** String (max length: 11)
- **Constraints:** Never Null

---

### TelephoneNo_s

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** Never Null

---

### FaxNo_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** Never Null

---

### AccountsCode_s

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** Never Null

---

### TypeOfSupply_s

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Never Null

---

### AdditionalInfo_txt

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### ContactName_s

**Properties:**

- **Type:** String (max length: 31)
- **Constraints:** Never Null

---

### EMailAddress_s

**Properties:**

- **Type:** String (max length: 51)
- **Constraints:** Never Null

---

### ConfirmationR

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### FaxNo2_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### EMailAddress2_s

**Properties:**

- **Type:** String (max length: 51)
- **Constraints:** Never Null

---

### Position_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** Never Null

---

### Archived_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### ContactName2_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** Never Null

---

### VATRate_r

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### TelephneNo1_s

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** Never Null

---

### LastOrdered

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### ApprovalStatus

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### CofaEmailContact

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

## Indexes

- **Field : **  //Name_s` - Kind: regular
Name_s  // - Kind: regular, Type: 7
- **Field : **  //Archived_b` - Kind: regular
Archived_b  // - Kind: regular, Type: 7
- **Field : **  //SupplierID_l` (Unique) - Kind: regular
SupplierID_l  // (Unique) - Kind: regular, Type: 7

## Many-to-One Relations

### SuppliersEntity

Links to table: [Suppliers](Suppliers.md)

- **Source Field:** `SupplierID_l`
- **Destination Field:** `SupplierID_l`

### SuppliersEntity

Links to table: [Suppliers](Suppliers.md)

- **Source Field:** `SupplierID_l`
- **Destination Field:** `SupplierID_l`

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
*Generated at: 2025-11-12T23:09:00Z*
