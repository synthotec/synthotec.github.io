---
layout : default
title : Tools
parent : Tables
---
# Tools

## Table Information

- **Table ID:** 2
- **UUID:** 730DDB789A822A45A2769798BE8BF8C3
- **Primary Key:** `Tool_ID`

## Table of Contents

- [Fields](#fields)
- [Indexes](#indexes)
- [Many-to-One Relations](#many-to-one-relations)
- [One-to-Many Relations](#one-to-many-relations)

## Fields

### NextUniqueLabelID_l

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Approved

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Short Name

**Properties:**

- **Type:** String
- **Constraints:** Never Null, Hidden

---

### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Tool_ID

**Properties:**

- **Type:** Date
- **Constraints:** Primary Key, Unique, Auto-sequence, Mandatory, Never Null, Not Modifiable

---

### PartNo

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### ShortName

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Never Null, Hidden

---

### Machine_Type

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### NumOfRows

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Pallet_Pic

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Setup_Sheet

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### OperatorRequired

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Robot_Prg_No

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### Pallet_Type_m

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### Tool_No

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** Unique, Mandatory, Never Null

---

### Impressions

**Properties:**

- **Type:** Picture
- **Constraints:** Mandatory, Never Null

---

### Date Created

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null, Not Enterable

---

### Box_Per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Boxes_Per_M_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Archive

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### CycleTimeSecs

**Properties:**

- **Type:** Boolean
- **Constraints:** Mandatory, Never Null

---

### PartWtGrams

**Properties:**

- **Type:** Boolean
- **Constraints:** Mandatory, Never Null

---

### RunnerWtGrams

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Regrind_MaxPercent

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Packed_Per_Hour

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Mandrells_per_Pallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Packing Box

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null, Hidden

---

### Dry_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### If on Concess

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### If Concess by N

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Total No Conces

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### No Concess Supp

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Concess End Dat

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### DryWeightText

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### ReasonToolOffsite_txt

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### IsToolOffsite_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### DateToolDueBack_d

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### TimePerPallet

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Picture

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Prodn Quan Min

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Production_Mandrell

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### Tool_Notes

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Conditioned

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Type

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Grey box Quan

**Properties:**

- **Type:** Date
- **Constraints:** Never Null, Hidden

---

### Cages_per_Mandrell

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Concession No

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** Never Null

---

### Customer Label

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** Never Null

---

### Additional_text_4_label

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### Nozzle

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** Never Null

---

### Separator

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### Prodn Quan Max

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Location

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Tool Mod

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** Never Null

---

### Initial Cust

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** Never Null

---

### Main Tool

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Additional_text

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### UseAddressLabels_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### UseUniqueIDLabels_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### LabelChoice_s

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** Mandatory, Never Null

---

### UseBagLabel_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### UseExtraID_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### UseLogisticslabel_b

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### NextUniqueIDLogistics_l

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Final_Customer

**Properties:**

- **Type:** String (max length: 35)
- **Constraints:** Never Null

---

### Weight_kitlabel

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### Kit_ProductID

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** Never Null

---

### Kit_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### Mandrel_OD

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### NumOfLayers

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### BagSealingMethod

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### PackedInColumns

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### RC_Sub_Sequence

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### RC_Additional_Seq

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### RC_Barcode

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### x3_sequence_packsheet

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### x4_sequence_packsheet

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### PackagingInstructionIssueDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### PackagingInstructionIssueName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### identifier_address

**Properties:**

- **Type:** String (max length: 2)
- **Constraints:** Never Null

---

### No_metalpallets_per_box

**Properties:**

- **Type:** Picture
- **Constraints:** Mandatory, Never Null

---

### two_boxnos

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### qty_delivered_flag

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### qty_pricechange

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### packrange_max

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### AQP

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### x2_uniqueIDlabels

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### DateChanged

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### PackagingInstructionIssueLevel

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### IsHandLoaded

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### OddLayerQuantity

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### SmallSide

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### LargeSide

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### AlternatingLayerQuantA

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### AlternatingLayerQuantB

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### ScalesFixedQuant

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### ExtraPackInfo

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### LabelOrigin

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### QRCode

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Amber

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### RunsSinceApproval

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### AmberCheckPercent

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### AmberManual

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### AmberManualWhen

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### AmberManualWho

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### AmberPQITriggered

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### RCText

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### ForeCast2015

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### ForeCast2015Update

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### ProductName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### PicBlob

**Properties:**

- **Type:** Unknown (18)
- **Constraints:** Never Null

---

### PicBlobTxt

**Properties:**

- **Type:** String
- **Constraints:** Never Null

---

### LogisticsPrefix

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### DataMatrix

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### Regrind

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### RegrindComments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### NotifyQuality

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### NotifyReason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### ToolReady

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### ToolOffsite

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### StatusUpdated

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### ToolDueDate

**Properties:**

- **Type:** Integer
- **Constraints:** Never Null

---

### PlanningWheelCycle

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### PlanningWheelHours

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### HotHalfID

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### HotHalfBooked

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### AmberTriggerTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** Never Null

---

### NewCalcedPartWeight

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### MaintenanceCycleTrigger

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### UsageWarningDays

**Properties:**

- **Type:** Date
- **Constraints:** Never Null

---

### ExtraSideLabel

**Properties:**

- **Type:** Real
- **Constraints:** Never Null

---

### QRtype

**Properties:**

- **Type:** Picture
- **Constraints:** Never Null

---

### RequiresChecking

**Properties:**

- **Type:** Real

---

### TemperatureTargetMin

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### TemperatureTargetMax

**Properties:**

- **Type:** Boolean
- **Constraints:** Never Null

---

### RobotHeads

**Properties:**

- **Type:** String (max length: 255)

---

### MigrationID

**Properties:**

- **Type:** Date

---

### ToolNoticeObject

**Properties:**

- **Type:** Unknown (21)

---

### ProductionHoldObject

**Properties:**

- **Type:** Unknown (21)

---

## Indexes

- **Field:** `MigrationID` - Kind: regular
- **Field:** `PartNo` - Kind: regular
- **Field:** `Archive` - Kind: regular
- **Field:** `ShortName` - Kind: regular
- **Field:** `two_boxnos` - Kind: regular
- **Field:** `HotHalfID` - Kind: regular
- **Field:** `Tool_No` - Kind: regular
- **Field:** `ProductID` - Kind: regular
- **Field:** `HotHalfBooked` - Kind: regular
- **Field:** `Tool_ID` (Unique) - Kind: regular

## Many-to-One Relations

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

### HotHalfEntity

Links to table: [HotHalfs](HotHalfs.md)

- **Source Field:** `HotHalfID`
- **Destination Field:** `ID`

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`

## One-to-Many Relations

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

### WheelCalendarSelection

- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`

### ProductStockTakeSelection

- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`

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

### ProductMaterialOptionsSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`

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

### CustomerSelection

- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`

### UsageMat1Selection

- **Source Field:** `UsageMatID`
- **This Table Field:** `Unique_ID`

### UsageMat2Selection

- **Source Field:** `UsageMatID2`
- **This Table Field:** `Unique_ID`

### UsageMat3Selection

- **Source Field:** `UsageMatID3`
- **This Table Field:** `Unique_ID`

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
*Generated at: 2025-11-12T23:08:44Z*
