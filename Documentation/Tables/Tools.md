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

- **Field:** `MigrationID` - Kind: regular, Type: 7
- **Field:** `PartNo` - Kind: regular, Type: 7
- **Field:** `Archive` - Kind: regular, Type: 7
- **Field:** `ShortName` - Kind: regular, Type: 7
- **Field:** `two_boxnos` - Kind: regular, Type: 7
- **Field:** `HotHalfID` - Kind: regular, Type: 7
- **Field:** `Tool_No` - Kind: regular, Type: 7
- **Field:** `ProductID` - Kind: regular, Type: 7
- **Field:** `HotHalfBooked` - Kind: regular, Type: 7
- **Field:** `Tool_ID` (Unique) - Kind: regular, Type: 7

## Many-to-One Relations

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### ToolsEntity

Links to table: [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

### HotHalfEntity

Links to table: [HotHalfs](HotHalfs.md)

- **Source Field:** `HotHalfID`
- **Destination Field:** `ID`
- **State:** 1

### ProductEntity

Links to table: [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** 1

## One-to-Many Relations

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

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`
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

### WheelCalendarSelection

- **Source Field:** `MatID`
- **This Table Field:** `Unique_ID`
- **State:** 1

### ProductStockTakeSelection

- **Source Field:** `WO`
- **This Table Field:** `Works_Order_No`
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

### ProductMaterialOptionsSelection

- **Source Field:** `MaterialID`
- **This Table Field:** `Unique_ID`
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

### Customer_OrderSelection

- **Source Field:** `Customer_Code`
- **This Table Field:** `Customer_Code`
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

### CustomerSelection

- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`
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
*Generated at: 2025-11-12T23:08:44Z*
