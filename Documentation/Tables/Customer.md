---
layout : default
title : Customer
parent : Tables
---
# Customer

## Table Information

- **Table ID:** 1
- **UUID:** 29D34E506C4DF7418EA055008A0624CE
- **Primary Key:** `Customer_Code`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Primary Key, Unique, Mandatory, Never Null, Not Modifiable

---

### Cust Name

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** Mandatory, Never Null

---

### Cust Addr1

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** Never Null

---

### Cust Addr2

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** Never Null

---

### Cust Addr3

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** Never Null

---

### Cust Addr4

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** Never Null

---

### Cust Postcode

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Cust Phone1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Cust Fax

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Cust Contact1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Email1

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### Cust Notes

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Cust Cum Ord

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Cust Inv Date

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### Cust Label1

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Mandatory, Never Null

---

### Cust Label2

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Never Null

---

### Cust label3

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Never Null

---

### Acknowledgement

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Acknow Contact

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Archive

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### CustContact2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPhone2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPosition1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPosition2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Email2

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### CofCRequired_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### DeliveryAddress_txt

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### SupplierCode

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### DeliveryDays

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### CustPosition3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPosition4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPosition5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPosition6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustContact3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustContact4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustContact5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustContact6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPhone3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPhone4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPhone5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### CustPhone6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Email3

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### Email4

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### Email5

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### Email6

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** Never Null

---

### BoxesPerPallet

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### OrderEmail

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### PalletTransportCost

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### TransportComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### RequiresMaterialCofA

**Properties:**

- **Type:** Real

---

### NtnSnrLocationCode

**Properties:**

- **Type:** String (max length: 255)

---

### Consignment

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### ConsignmentLocationID

**Properties:**

- **Type:** Date

---

### MigrationID

**Properties:**

- **Type:** String

---

### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

### TransportInstructionFileID

**Properties:**

- **Type:** Date

---

## Indexes

- **Field:** `Customer_Code` (Unique) - Kind: regular, Type: 7
- **Field:** `Cust Addr3` - Kind: regular, Type: 7
- **Field:** `Consignment` - Kind: regular, Type: 7
- **Field:** `NtnSnrLocationCode` - Kind: regular, Type: 7
- **Field:** `MigrationID` - Kind: regular, Type: 7
- **Field:** `Archive` - Kind: regular, Type: 7
- **Field:** `ConsignmentLocationID` - Kind: regular, Type: 7

## Many-to-One Relations

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** 1

### CustomerEntity

Links to table: [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** 1

### Stock_LocationEntity

Links to table: [Stock_Location](Stock_Location.md)

- **Source Field:** `ConsignmentLocationID`
- **Destination Field:** `StockLocationID_l`
- **State:** 1

### TransportInstructionFileEntity

Links to table: [File](File.md)

- **Source Field:** `TransportInstructionFileID`
- **Destination Field:** `ID`
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

### Customer_OrderSelection

- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`
- **State:** 1

### ForecastSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`
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
*Generated at: 2025-11-12T23:08:43Z*
