---
layout : default
title : Customer
parent : Tables
---
# Customer

📊 **Overview:** 56 Fields | 7 Indexes | 4 Many-to-One Relations | 132 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 1
- **UUID:** 29D34E506C4DF7418EA055008A0624CE
- **Primary Key:** 🔑 `Customer_Code`
- **Generated:** 🕐 2025-11-12T23:08:43Z

---

## 📑 Table of Contents

- [📋 Fields](#fields) (56)
- [🔍 Indexes](#indexes) (7)
- [🔗 Many-to-One Relations](#many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#one-to-many-relations) (132)

---

## 📋 Fields

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Customer_Code** | `String` (3) | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Cust Name | `String` (35) | ⚠️ Required, 🚫 Not Null | - |
| Cust Addr1 | `String` (35) | 🚫 Not Null | - |
| Cust Addr2 | `String` (35) | 🚫 Not Null | - |
| Cust Addr3 | `String` (35) | 🚫 Not Null | - |
| Cust Addr4 | `String` (35) | 🚫 Not Null | - |
| Cust Postcode | `String` (20) | 🚫 Not Null | - |
| Cust Phone1 | `String` (20) | 🚫 Not Null | - |
| Cust Fax | `String` (20) | 🚫 Not Null | - |
| Cust Contact1 | `String` (20) | 🚫 Not Null | - |
| Email1 | `String` (80) | 🚫 Not Null | - |
| Cust Notes | `String` | 🚫 Not Null | - |
| Cust Cum Ord | `Boolean` | 🚫 Not Null | - |
| Cust Inv Date | `Integer` | 🚫 Not Null | - |
| Cust Label1 | `String` (25) | ⚠️ Required, 🚫 Not Null | - |
| Cust Label2 | `String` (25) | 🚫 Not Null | - |
| Cust label3 | `String` (25) | 🚫 Not Null | - |
| Acknowledgement | `Real` | 🚫 Not Null | - |
| Acknow Contact | `String` (30) | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |
| CustContact2 | `String` (20) | 🚫 Not Null | - |
| CustPhone2 | `String` (20) | 🚫 Not Null | - |
| CustPosition1 | `String` (20) | 🚫 Not Null | - |
| CustPosition2 | `String` (20) | 🚫 Not Null | - |
| Email2 | `String` (80) | 🚫 Not Null | - |
| CofCRequired_b | `Real` | 🚫 Not Null | - |
| DeliveryAddress_txt | `String` | 🚫 Not Null | - |
| SupplierCode | `String` (30) | 🚫 Not Null | - |
| DeliveryDays | `Picture` | 🚫 Not Null | - |
| CustPosition3 | `String` (20) | 🚫 Not Null | - |
| CustPosition4 | `String` (20) | 🚫 Not Null | - |
| CustPosition5 | `String` (20) | 🚫 Not Null | - |
| CustPosition6 | `String` (20) | 🚫 Not Null | - |
| CustContact3 | `String` (20) | 🚫 Not Null | - |
| CustContact4 | `String` (20) | 🚫 Not Null | - |
| CustContact5 | `String` (20) | 🚫 Not Null | - |
| CustContact6 | `String` (20) | 🚫 Not Null | - |
| CustPhone3 | `String` (20) | 🚫 Not Null | - |
| CustPhone4 | `String` (20) | 🚫 Not Null | - |
| CustPhone5 | `String` (20) | 🚫 Not Null | - |
| CustPhone6 | `String` (20) | 🚫 Not Null | - |
| Email3 | `String` (80) | 🚫 Not Null | - |
| Email4 | `String` (80) | 🚫 Not Null | - |
| Email5 | `String` (80) | 🚫 Not Null | - |
| Email6 | `String` (80) | 🚫 Not Null | - |
| BoxesPerPallet | `Boolean` | 🚫 Not Null | - |
| OrderEmail | `String` (255) | 🚫 Not Null | - |
| PalletTransportCost | `Boolean` | 🚫 Not Null | - |
| TransportComment | `String` (255) | 🚫 Not Null | - |
| RequiresMaterialCofA | `Real` | - | - |
| NtnSnrLocationCode | `String` (255) | - | - |
| Consignment | `Real` | 🚫 Not Null | - |
| ConsignmentLocationID | `Date` | - | - |
| MigrationID | `String` | - | - |
| LastMigration | `String` (255) | - | - |
| TransportInstructionFileID | `Date` | - | - |

### Detailed Information

#### 🔑 Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚠️ Mandatory, 🚫 Never Null, 🔒 Not Modifiable

---

#### Cust Name

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Cust Addr1

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Addr2

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Addr3

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Addr4

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** 🚫 Never Null

---

#### Cust Postcode

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Cust Phone1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Cust Fax

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Cust Contact1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Email1

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Cust Notes

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Cust Cum Ord

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Cust Inv Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Cust Label1

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Cust Label2

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Cust label3

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### Acknowledgement

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Acknow Contact

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Archive

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CustContact2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition1

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition2

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Email2

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### CofCRequired_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DeliveryAddress_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### SupplierCode

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### DeliveryDays

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### CustPosition3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPosition6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustContact6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone3

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone4

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone5

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### CustPhone6

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Email3

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Email4

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Email5

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Email6

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### BoxesPerPallet

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### OrderEmail

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PalletTransportCost

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TransportComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### RequiresMaterialCofA

**Properties:**

- **Type:** Real

---

#### NtnSnrLocationCode

**Properties:**

- **Type:** String (max length: 255)

---

#### Consignment

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ConsignmentLocationID

**Properties:**

- **Type:** Date

---

#### MigrationID

**Properties:**

- **Type:** String

---

#### LastMigration

**Properties:**

- **Type:** String (max length: 255)

---

#### TransportInstructionFileID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Customer_Code` | - | regular | ✨ Yes |
| `Cust Addr3` | - | regular | - |
| `Consignment` | - | regular | - |
| `NtnSnrLocationCode` | - | regular | - |
| `MigrationID` | - | regular | - |
| `Archive` | - | regular | - |
| `ConsignmentLocationID` | - | regular | - |

### Detailed Information

- **Field:** `Customer_Code` ✨ **(Unique)**
  - **Kind:** regular
- **Field:** `Cust Addr3`
  - **Kind:** regular
- **Field:** `Consignment`
  - **Kind:** regular
- **Field:** `NtnSnrLocationCode`
  - **Kind:** regular
- **Field:** `MigrationID`
  - **Kind:** regular
- **Field:** `Archive`
  - **Kind:** regular
- **Field:** `ConsignmentLocationID`
  - **Kind:** regular

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | - |
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | - |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `ConsignmentLocationID` → `StockLocationID_l` | - |
| `TransportInstructionFileEntity` | [File](File.md) | `TransportInstructionFileID` → `ID` | - |

### Detailed Information

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

---

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`

---

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `ConsignmentLocationID`
- **Destination Field:** `StockLocationID_l`

---

#### TransportInstructionFileEntity

**Links to:** [File](File.md)

- **Source Field:** `TransportInstructionFileID`
- **Destination Field:** `ID`

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ToolsSelection` | - | `ProductID` → `Product_ID` | - |
| `Customer_OrderSelection` | - | `Product_ID` → `Product_ID` | - |
| `OrderPickRequestSelection` | - | `PickRequestID` → `ID` | - |
| `Customer_OrderSelection` | - | `Material_ID` → `Unique_ID` | - |
| `WorksOrderSelection` | - | `ToolID` → `Tool_ID` | - |
| `Stock_MovementSelection` | - | `Works_Order_No_l` → `Works_Order_No` | - |
| `CofCSelection` | - | `Works_Order_No` → `Works_Order_No` | - |
| `CofCSelection` | - | `Petes No` → `Petes_No` | - |
| `Finished_StockSelection` | - | `Works_Order_No` → `Works_Order_No` | - |
| `Product_OptionSelection` | - | `Product ID` → `Product_ID` | - |
| `Product_OptionSelection` | - | `Material_ID` → `Unique_ID` | - |
| `NonConformanceSelection` | - | `Tool_ID` → `Tool_ID` | - |
| `SuppliesSelection` | - | `SupplierID_l` → `SupplierID_l` | - |
| `PurchasesSelection` | - | `SupplierID_l` → `SupplierID_l` | - |
| `PurchaseInfoSelection` | - | `OrderNo_l` → `OrderNo_l` | - |
| `GaugesSelection` | - | `Product_ID` → `Product_ID` | - |
| `GrippersSelection` | - | `Product_ID` → `Product_ID` | - |
| `RMCSelection` | - | `MaterialID_l` → `Unique_ID` | - |
| `ProductReturnSelection` | - | `ProductID_l` → `Product_ID` | - |
| `ProductReturnWorksOrderSelection` | - | `ReturnID_l` → `ReturnID_l` | - |
| `ProductReturnWorksOrderSelection` | - | `Works_Order_No_l` → `Works_Order_No` | - |
| `LanguageTagSelection` | - | `Language_ID` → `ID_l` | - |
| `BoxLabelsSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductPackagingSelection` | - | `SuppliesID` → `UniqueID_i` | - |
| `SuppliesSelection` | - | `PackagingCat` → `ID` | - |
| `ToolLogSelection` | - | `Tool_ID` → `Tool_ID` | - |
| `Stock_MovementSelection` | - | `To_Location_l` → `StockLocationID_l` | - |
| `MaterialCheckHistorySelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `PurchaseInfoSelection` | - | `SuppliesID_i` → `UniqueID_i` | - |
| `RealTimeSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductPackagingSelection` | - | `ProductID` → `Product_ID` | - |
| `WheelCalendarSelection` | - | `MatID` → `Unique_ID` | - |
| `ProductStockTakeSelection` | - | `WO` → `Works_Order_No` | - |
| `ProductStocktakeSelection` | - | `ProductID` → `Product_ID` | - |
| `ConsignmentEntrySelection` | - | `ProductID` → `Product_ID` | - |
| `ScrapSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ApprovalsSelection` | - | `ToolID` → `Tool_ID` | - |
| `RTSUMSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `RealTimeSelection` | - | `DownReason` → `ID` | - |
| `WorkRequestCommentsSelection` | - | `WorkRequestID` → `ID` | - |
| `BOMSelection` | - | `ProductID` → `Product_ID` | - |
| `BOMSelection` | - | `MaterialID` → `Unique_ID` | - |
| `PurchaseInfoSelection` | - | `NominalCode` → `ID` | - |
| `MaterialCheckHistorySelection` | - | `MaterialID` → `Unique_ID` | - |
| `CalibrationsSelection` | - | `EquipmentID` → `ID` | - |
| `SupplierDocumentationSelection` | - | `SupplierID` → `SupplierID_l` | - |
| `ProductSelection` | - | `PalletMethodID` → `ID` | - |
| `StaffPermissionsSelection` | - | `PermissionID` → `ID` | - |
| `StaffPermissionsSelection` | - | `StaffID` → `StaffID` | - |
| `CalibrationProceduresSelection` | - | `EquipmentID` → `ID` | - |
| `CalibrationResultsSelection` | - | `CalibrationID` → `ID` | - |
| `PlanningWheelSelection` | - | `MaterialID` → `Unique_ID` | - |
| `Product_OptionSelection` | - | `Customer Code` → `Customer_Code` | - |
| `Finished_StockSelection` | - | `LocationID_l` → `StockLocationID_l` | - |
| `PalletSelection` | - | `ProductID` → `Product_ID` | - |
| `LinkedBoxLabelsSelection` | - | `LinkedBoxID` → `ID` | - |
| `PurchaseReceiptsSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `RMCSelection` | - | `PurchaseInfoID` → `UniqueID_l` | - |
| `PurchaseReceiptsSelection` | - | `RMC` → `RMCNo_l` | - |
| `BoxLabelsSelection` | - | `ToolID` → `Tool_ID` | - |
| `WorksOrderSelection` | - | `ProductID_l` → `Product_ID` | - |
| `ProductSelection` | - | `EmojiID` → `ID` | - |
| `WorkRequestsSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolMaintenanceLogSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolMaintenanceLogSelection` | - | `WorkRequestID` → `ID` | - |
| `MachineMaintenanceLogSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `MachineMaintenanceRequirementsSelection` | - | `MachineMaintenanceActionID` → `ID` | - |
| `DB_VariablesSelection` | - | `StaffID` → `StaffID` | - |
| `PackingInstructionFilesSelection` | - | `ProductID` → `Product_ID` | - |
| `WorkRequestCommentsSelection` | - | `StaffID` → `StaffID` | - |
| `BoxLabelsSelection` | - | `PalletID` → `ID` | - |
| `FirstRealTimeSensorExceptionsSelection` | - | `FirstRealTimeID` → `ID` | - |
| `LastRealTimeSensorExceptionsSelection` | - | `LastRealTimeID` → `ID` | - |
| `RealTimeSensorExceptionsSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `RealTimeSensorExceptionsSelection` | - | `StaffID` → `StaffID` | - |
| `RealTimeMachinesSelection` | - | `DownReason` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolTemperatureTargetSelection` | - | `ZoneID` → `ID` | - |
| `ToolTemperatureTargetSelection` | - | `StaffID` → `StaffID` | - |
| `PalletSelection` | - | `LocationID` → `ID` | - |
| `LocationSelection` | - | `ParentLocationID` → `ID` | - |
| `ToolDocumentSelection` | - | `ToolID` → `Tool_ID` | - |
| `OrderPickRequestSelection` | - | `CustomerOrderID` → `Petes_No` | - |
| `WheelCalendarSelection` | - | `ProductID` → `Product_ID` | - |
| `ProductMaterialOptionsSelection` | - | `MaterialID` → `Unique_ID` | - |
| `ProductMaterialOptionsSelection` | - | `ProductID` → `Product_ID` | - |
| `MaterialStockTakeSelection` | - | `RMC` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection1` | - | `RMC1` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection2` | - | `RMC2` → `RMCNo_l` | - |
| `MaterialCheckHistorySelection3` | - | `RMC3` → `RMCNo_l` | - |
| `PalletSelection` | - | `OrderPickRequestID` → `ID` | - |
| `BoxLabelsSelection` | - | `OrderPickRequestID` → `ID` | - |
| `PickRequestSelection` | - | `Customer` → `Customer_Code` | - |
| `BoxLabelsSelection` | - | `CofCID` → `Cert_Of_Conformance_No` | - |
| `PalletSelection` | - | `CofCID` → `Cert_Of_Conformance_No` | - |
| `CofCSelection` | - | `Advice_Note_No` → `Advice_Note_No` | - |
| `CofCSelection` | - | `LocationID_l` → `StockLocationID_l` | - |
| `CofCSelection` | - | `ProductID_l` → `Product_ID` | - |
| `PickRequestSelection` | - | `AdviceNoteID` → `ID` | - |
| `MaterialStockSelection` | - | `MaterialID` → `Unique_ID` | - |
| `MaterialStockSelection` | - | `RMC` → `RMCNo_l` | - |
| `MaterialStockSelection` | - | `LocationID` → `ID` | - |
| `WheelCalendarSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `PrintJobSelection` | - | `PrinterID` → `ID` | - |
| `PrintJobSelection` | - | `RelatedUUID` → `UUID` | - |
| `PrintJobSelection` | - | `StaffID` → `StaffID` | - |
| `PlanningWheelSelection` | - | `ToolID` → `Tool_ID` | - |
| `BoxLabelsSelection` | - | `Stock_LocationID` → `StockLocationID_l` | - |
| `ShiftSummaryDetailSelection` | - | `ShiftSummaryID` → `ID` | - |
| `ShiftSummarySelection` | - | `StaffID` → `StaffID` | - |
| `ShiftSummaryDetailSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `ProductSelection` | - | `DefMatID` → `Unique_ID` | - |
| `StatusUpdatedBoxLabelsSelection` | - | `StatusUpdatedStaffID` → `StaffID` | - |
| `ErrorDetailSelection` | - | `ErrorID` → `ID` | - |
| `Customer_OrderSelection` | - | `Product_OptionID` → `ID` | - |
| `ForecastSelection` | - | `ProductID` → `Product_ID` | - |
| `ToolsSelection` | - | `HotHalfID` → `ID` | - |
| `UsageMat1Selection` | - | `UsageMatID` → `Unique_ID` | - |
| `UsageMat2Selection` | - | `UsageMatID2` → `Unique_ID` | - |
| `UsageMat3Selection` | - | `UsageMatID3` → `Unique_ID` | - |
| `QualitySystemProceduresSelection` | - | `ProductID` → `Product_ID` | - |
| `ApprovalsSelection` | - | `Customer` → `Customer_Code` | - |
| `BOMSelection` | - | `Customer` → `Customer_Code` | - |
| `WorksOrderSelection` | - | `MaterialID` → `Unique_ID` | - |
| `Product_OptionSelection` | - | `Tool ID` → `Tool_ID` | - |
| `CustomerContactsSelection` | - | `Customer` → `Customer_Code` | - |
| `ProductPackagingSelection` | - | `Customer` → `Customer_Code` | - |
| `ToolNoticeSelection` | - | `ToolID` → `Tool_ID` | - |
| `ToolNoticeSelection` | - | `StaffID` → `StaffID` | - |
| `ToolNoticeWorksOrderSelection` | - | `ToolNoticeID` → `ToolID` | - |
| `ToolNoticeWorksOrderSelection` | - | `WorksOrder` → `Works_Order_No` | - |
| `DeactivatedToolNoticeSelection` | - | `DeactivatedStaffID` → `StaffID` | - |

### Detailed Information

#### ToolsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### Customer_OrderSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

---

#### OrderPickRequestSelection

- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`

---

#### Customer_OrderSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`

---

#### WorksOrderSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### Stock_MovementSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

---

#### CofCSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`

---

#### CofCSelection

- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`

---

#### Finished_StockSelection

- **Source Field:** `Works_Order_No`
- **This Table Field:** `Works_Order_No`

---

#### Product_OptionSelection

- **Source Field:** `Product ID`
- **This Table Field:** `Product_ID`

---

#### Product_OptionSelection

- **Source Field:** `Material_ID`
- **This Table Field:** `Unique_ID`

---

#### NonConformanceSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`

---

#### SuppliesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`

---

#### PurchasesSelection

- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`

---

#### PurchaseInfoSelection

- **Source Field:** `OrderNo_l`
- **This Table Field:** `OrderNo_l`

---

#### GaugesSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

---

#### GrippersSelection

- **Source Field:** `Product_ID`
- **This Table Field:** `Product_ID`

---

#### RMCSelection

- **Source Field:** `MaterialID_l`
- **This Table Field:** `Unique_ID`

---

#### ProductReturnSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

---

#### ProductReturnWorksOrderSelection

- **Source Field:** `ReturnID_l`
- **This Table Field:** `ReturnID_l`

---

#### ProductReturnWorksOrderSelection

- **Source Field:** `Works_Order_No_l`
- **This Table Field:** `Works_Order_No`

---

#### LanguageTagSelection

- **Source Field:** `Language_ID`
- **This Table Field:** `ID_l`

---

#### BoxLabelsSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### ProductPackagingSelection

- **Source Field:** `SuppliesID`
- **This Table Field:** `UniqueID_i`

---

#### SuppliesSelection

- **Source Field:** `PackagingCat`
- **This Table Field:** `ID`

---

#### ToolLogSelection

- **Source Field:** `Tool_ID`
- **This Table Field:** `Tool_ID`

---

#### Stock_MovementSelection

- **Source Field:** `To_Location_l`
- **This Table Field:** `StockLocationID_l`

---

#### MaterialCheckHistorySelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### PurchaseInfoSelection

- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`

---

#### RealTimeSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### ProductPackagingSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### WheelCalendarSelection

- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`

---

#### ProductStockTakeSelection

- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`

---

#### ProductStocktakeSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ConsignmentEntrySelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ScrapSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### ApprovalsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### RTSUMSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### RealTimeSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`

---

#### WorkRequestCommentsSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`

---

#### BOMSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### BOMSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### PurchaseInfoSelection

- **Source Field:** `NominalCode`
- **This Table Field:** `ID`

---

#### MaterialCheckHistorySelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### CalibrationsSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`

---

#### SupplierDocumentationSelection

- **Source Field:** `SupplierID`
- **This Table Field:** `SupplierID_l`

---

#### ProductSelection

- **Source Field:** `PalletMethodID`
- **This Table Field:** `ID`

---

#### StaffPermissionsSelection

- **Source Field:** `PermissionID`
- **This Table Field:** `ID`

---

#### StaffPermissionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### CalibrationProceduresSelection

- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`

---

#### CalibrationResultsSelection

- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`

---

#### PlanningWheelSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### Product_OptionSelection

- **Source Field:** `Customer Code`
- **This Table Field:** `Customer_Code`

---

#### Finished_StockSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`

---

#### PalletSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### LinkedBoxLabelsSelection

- **Source Field:** `LinkedBoxID`
- **This Table Field:** `ID`

---

#### PurchaseReceiptsSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`

---

#### RMCSelection

- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`

---

#### PurchaseReceiptsSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

---

#### BoxLabelsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### WorksOrderSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

---

#### ProductSelection

- **Source Field:** `EmojiID`
- **This Table Field:** `ID`

---

#### WorkRequestsSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolMaintenanceLogSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolMaintenanceLogSelection

- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`

---

#### MachineMaintenanceLogSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

---

#### MachineMaintenanceRequirementsSelection

- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`

---

#### DB_VariablesSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### PackingInstructionFilesSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### WorkRequestCommentsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### BoxLabelsSelection

- **Source Field:** `PalletID`
- **This Table Field:** `ID`

---

#### FirstRealTimeSensorExceptionsSelection

- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`

---

#### LastRealTimeSensorExceptionsSelection

- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`

---

#### RealTimeSensorExceptionsSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### RealTimeSensorExceptionsSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### RealTimeMachinesSelection

- **Source Field:** `DownReason`
- **This Table Field:** `ID`

---

#### ToolTemperatureTargetSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolTemperatureTargetSelection

- **Source Field:** `ZoneID`
- **This Table Field:** `ID`

---

#### ToolTemperatureTargetSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### PalletSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`

---

#### LocationSelection

- **Source Field:** `ParentLocationID`
- **This Table Field:** `ID`

---

#### ToolDocumentSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### OrderPickRequestSelection

- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`

---

#### WheelCalendarSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ProductMaterialOptionsSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### ProductMaterialOptionsSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### MaterialStockTakeSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

---

#### MaterialCheckHistorySelection1

- **Source Field:** `RMC1`
- **This Table Field:** `RMCNo_l`

---

#### MaterialCheckHistorySelection2

- **Source Field:** `RMC2`
- **This Table Field:** `RMCNo_l`

---

#### MaterialCheckHistorySelection3

- **Source Field:** `RMC3`
- **This Table Field:** `RMCNo_l`

---

#### PalletSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`

---

#### BoxLabelsSelection

- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`

---

#### PickRequestSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### BoxLabelsSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`

---

#### PalletSelection

- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`

---

#### CofCSelection

- **Source Field:** `Advice_Note_No`
- **This Table Field:** `Advice_Note_No`

---

#### CofCSelection

- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`

---

#### CofCSelection

- **Source Field:** `ProductID_l`
- **This Table Field:** `Product_ID`

---

#### PickRequestSelection

- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`

---

#### MaterialStockSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### MaterialStockSelection

- **Source Field:** `RMC`
- **This Table Field:** `RMCNo_l`

---

#### MaterialStockSelection

- **Source Field:** `LocationID`
- **This Table Field:** `ID`

---

#### WheelCalendarSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### PrintJobSelection

- **Source Field:** `PrinterID`
- **This Table Field:** `ID`

---

#### PrintJobSelection

- **Source Field:** `RelatedUUID`
- **This Table Field:** `UUID`

---

#### PrintJobSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### PlanningWheelSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### BoxLabelsSelection

- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`

---

#### ShiftSummaryDetailSelection

- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`

---

#### ShiftSummarySelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### ShiftSummaryDetailSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### ProductSelection

- **Source Field:** `DefMatID`
- **This Table Field:** `Unique_ID`

---

#### StatusUpdatedBoxLabelsSelection

- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`

---

#### ErrorDetailSelection

- **Source Field:** `ErrorID`
- **This Table Field:** `ID`

---

#### Customer_OrderSelection

- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`

---

#### ForecastSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ToolsSelection

- **Source Field:** `HotHalfID`
- **This Table Field:** `ID`

---

#### UsageMat1Selection

- **Source Field:** `UsageMatID`
- **This Table Field:** `Unique_ID`

---

#### UsageMat2Selection

- **Source Field:** `UsageMatID2`
- **This Table Field:** `Unique_ID`

---

#### UsageMat3Selection

- **Source Field:** `UsageMatID3`
- **This Table Field:** `Unique_ID`

---

#### QualitySystemProceduresSelection

- **Source Field:** `ProductID`
- **This Table Field:** `Product_ID`

---

#### ApprovalsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### BOMSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### WorksOrderSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

---

#### Product_OptionSelection

- **Source Field:** `Tool ID`
- **This Table Field:** `Tool_ID`

---

#### CustomerContactsSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### ProductPackagingSelection

- **Source Field:** `Customer`
- **This Table Field:** `Customer_Code`

---

#### ToolNoticeSelection

- **Source Field:** `ToolID`
- **This Table Field:** `Tool_ID`

---

#### ToolNoticeSelection

- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`

---

#### ToolNoticeWorksOrderSelection

- **Source Field:** `ToolNoticeID`
- **This Table Field:** `ToolID`

---

#### ToolNoticeWorksOrderSelection

- **Source Field:** `WorksOrder`
- **This Table Field:** `Works_Order_No`

---

#### DeactivatedToolNoticeSelection

- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-12T23:08:43Z*
