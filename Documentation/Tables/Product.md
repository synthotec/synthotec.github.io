---
layout: default
title: Product
parent: Tables
---
# Product Table
No description for this table has been created yet.

*[Primary Key]: This field is the primary key of the table
*[Unique]: 4D will not allow this field to be saved if it contains a value already used
*[Mandatory]: 4D will not allow this record to be saved if this field is equal to null
*[Indexed]: 4D will create an index for this field allowing for faster queries at the expense of disk storage
*[Exposed]: Field is available with remote ORDA connections
*[Auto Filled]: 4D will fill this field automatically when saving the record if it is equal to null
*[Type]: Type of data held within this field
*[Read Only]: No setter/write functionality has been added to this field
*[Alias Path]: The path that 4D will follow when this alias is called
*[Description]: This description has been manually added to this item for documentation purposes
*[Inverse Name]: The name of the inverse relationship from the corresponding table
*[Related Table]: The table that this relationship corresponds to
*[Local]: Function to be called on local 4D client in user space instead of remotely on server
## Fields

|Name|Type|Primary Key|Unique|Mandatory|Indexed|Exposed|Auto Filled|Description|
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|**Product_ID**|number|✔️|✔️||✔️|✔️|✔️||
|Archive|bool|||||✔️|||
|AverageRunLength|number|||||✔️|||
|BottomPackTimeOverride|number|||||✔️|||
|BottomPackTimeTarget|number|||||✔️|||
|Box_Per_Pallet|number|||||✔️|||
|Boxes_per_M_Pallet|number|||||✔️|||
|Cages_per_Mandrell|number|||||✔️|||
|ClosedLoopPercent|number|||||✔️|||
|Cond_Cycl_Lght|number|||||✔️|||
|Conditioned|bool|||||✔️|||
|ConsignmentOrder|bool|||||✔️|||
|ControlPlanLink1_txt|string|||||✔️|||
|ControlPlanLink2_txt|string|||||✔️|||
|Conversion_Figure|string|||||✔️|||
|CoveredByWheel|number|||||✔️|||
|Cust Part No|string||||✔️|✔️|||
|Danzas_ID|number|||||✔️|||
|Danzas_ID1|number|||||✔️|||
|Danzas_ID2|number|||||✔️|||
|DefMatID|number||||✔️|✔️|||
|Drawing No|string|||||✔️|||
|EmojiID|number||||✔️|✔️|||
|Extra_Text|string|||||✔️|||
|Field_80|string|||||✔️|||
|ForecastOutstanding|number|||||✔️|||
|ForecastOutstandingCurrentYear|number|||||✔️|||
|ForecastQty|number|||||✔️|||
|HoursOverride|number|||||✔️|||
|Initial_Customer|string|||||✔️|||
|Inspect Method1|string|||||✔️|||
|Inspect Method2|string|||||✔️|||
|Inspect Method3|string|||||✔️|||
|Inspect Method4|string|||||✔️|||
|Inspect Method5|string|||||✔️|||
|Inspect_freq_cycle|number|||||✔️|||
|Inspect_Freq_MIN|number|||||✔️|||
|Inspect_freq_period|string|||||✔️|||
|Inspect_Freq_qty|number|||||✔️|||
|Inspection Issue|number|||||✔️|||
|Inspection IssueDate|date|||||✔️|||
|Inspection IssuedBy|string|||||✔️|||
|Issue Date|date|||||✔️|||
|Issue No|string|||||✔️|||
|LastMigration|string|||||✔️|||
|MagicNumber|number|||||✔️|||
|Mandrel_OD|number|||||✔️|||
|Mandrells_per_Pallet|number|||||✔️|||
|MBAmount|number|||||✔️|||
|MBType|string|||||✔️|||
|MigrationID|number||||✔️|✔️|||
|Min Order Quan|number|||||✔️|||
|NoInBox|number|||||✔️|||
|NumOfSquirts|number|||||✔️|||
|Odette_PO|string|||||✔️|||
|OperatorRequired|bool|||||✔️|||
|Our Part No|string||||✔️|✔️|||
|OurBatchSize|number|||||✔️|||
|OurMinimum|number|||||✔️|||
|Packed_Per_Hour|number|||||✔️|||
|PackingInstructionsFileBlob|blob|||||✔️|||
|PackingInstructionsFileName|string|||||✔️|||
|Pallet_Pic|image|||||✔️|||
|Pallet_Type_m|string|||||✔️|||
|PalletMethodID|number|||||✔️|||
|Part Name|string|||||✔️|||
|Part_Colour|string|||||✔️|||
|Part_No_Colour|number|||||✔️|||
|Patrol Inspect1|string|||||✔️|||
|Patrol Inspect2|string|||||✔️|||
|Patrol Inspect3|string|||||✔️|||
|Patrol Inspect4|string|||||✔️|||
|PlannedRoute|number|||||✔️|||
|Price Quan|number|||||✔️|||
|PrimaryRoute|number||||✔️|✔️|||
|PrioritizeStandardOrders|bool|||||✔️|||
|Production_Mandrell|string|||||✔️|||
|Programme_No|string|||||✔️|||
|Quality_FormNo|number|||||✔️|||
|Quality_IssueDate|date|||||✔️|||
|Quality_Issuedby|string|||||✔️|||
|Quality_ReferenceNo|string|||||✔️|||
|QuotedCycle|number|||||✔️|||
|Reason_4_Issue_Change|string|||||✔️|||
|Regrnd allwd pc|number|||||✔️|||
|Robot_Prg_No|string|||||✔️|||
|RoutedElsewhere|number|||||✔️|||
|RunsPerForecast|number|||||✔️|||
|SecondCode|string|||||✔️|||
|SecondLocation|string|||||✔️|||
|Setup_Sheet|bool|||||✔️|||
|Short Name|string|||||✔️|||
|StockTowardsForecast|number|||||✔️|||
|SubContainerName|string|||||✔️|||
|SubContainerQty|number|||||✔️|||
|TimePerPallet|number|||||✔️|||
|Tolerance_High|number|||||✔️|||
|Tolerance_Low|number|||||✔️|||
|Top_Up_No|number|||||✔️|||
|TotalPackInstances|number|||||✔️|||
|TotalPackString|string|||||✔️|||
|TotalPackTime|number|||||✔️|||
|UsedSinceBill|number|||||✔️|||
|WareHouseMethod|string|||||✔️|||
|Water_Squirt_prog_number|number|||||✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Description|
|:---|:---:|:---:|:---:|:---:|
|ID|Product_ID|number|||
|UnicodeChar|Emoji|string|✔️||

## Calculated Fields

|Name|Type|Read Only|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|CustomerPartName|string|✔️|✔️||
|Emoji|string|✔️|||
|HasMigrationID|bool|✔️|||
|MainToolRegrind|bool||||
|OurPartName|string||✔️||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|EmojisEntity|[Emojis](Emojis.md)|ProductSelection|✔️||
|MaterialEntity|[Material](Material.md)|ProductSelection|✔️||
|PalletMethodsEntity|[PalletMethods](PalletMethods.md)|ProductSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|BOMSelection|[BOM](BOM.md)|ProductEntity|✔️||
|CofCSelection|[CofC](CofC.md)|ProductEntity|✔️||
|ConsignmentEntrySelection|[ConsignmentEntry](ConsignmentEntry.md)|ProductEntity|✔️||
|Customer_OrderSelection|[Customer_Order](Customer_Order.md)|ProductEntity|✔️||
|ForecastSelection|[Forecast](Forecast.md)|ProductEntity|✔️||
|GaugesSelection|[Gauges](Gauges.md)|ProductEntity|✔️||
|GrippersSelection|[Grippers](Grippers.md)|ProductEntity|✔️||
|PackingInstructionFilesSelection|[PackingInstructionFiles](PackingInstructionFiles.md)|ProductEntity|✔️||
|PalletSelection|[Pallet](Pallet.md)|ProductEntity|✔️||
|Product_OptionSelection|[Product_Option](Product_Option.md)|ProductEntity|✔️||
|ProductMaterialOptionsSelection|[ProductMaterialOptions](ProductMaterialOptions.md)|ProductEntity|✔️||
|ProductPackagingSelection|[ProductPackaging](ProductPackaging.md)|ProductEntity|✔️||
|ProductReturnSelection|[ProductReturn](ProductReturn.md)|ProductEntity|✔️||
|ProductStocktakeSelection|[ProductStockTake](ProductStockTake.md)|ProductEntity|✔️||
|QualitySystemProceduresSelection|[QualitySystemProcedures](QualitySystemProcedures.md)|ProductEntity|✔️||
|ToolsSelection|[Tools](Tools.md)|ProductEntity|✔️||
|WheelCalendarSelection|[WheelCalendar](WheelCalendar.md)|ProductEntity|✔️||
|WorksOrderSelection|[WorksOrder](WorksOrder.md)|ProductEntity|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Product.4dm)

|Name|Local|Description|
|:---|:---:|:---:|
|getMigrationSettings()|✔️||
|populateEmojis()|✔️||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductEntity.4dm)

|Name|Local|Description|
|:---|:---:|:---:|
|getRobotHeadList()|✔️||
|getMainTool()|✔️||
|getPreviousPickRequestQuantity()|✔️||
|getFinishedStock()|✔️||
|getQuarantinedStock()|✔️||
|getWIP()|✔️||
|getPlannedProduction()|✔️||
|getPickRequestedQuantity()|✔️||
|getAvailableStock()|✔️||
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||