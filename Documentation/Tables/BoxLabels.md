---
layout: default
title: BoxLabels ⌛
parent: Tables
---
# BoxLabels Table
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
|**ID**|number|✔️|✔️|✔️|✔️|✔️|✔️||
|BoxNumber|number|||||✔️|||
|CofCID|number||||✔️|✔️|||
|Comments|string|||||✔️|||
|Date|date|||||✔️|||
|DateTime|string|||||✔️|||
|LastMigration|string|||||✔️|||
|LinkedBoxID|number||||✔️|✔️|||
|Mandrels|number|||||✔️|||
|MigrationID|number|||||✔️|||
|NotMade|bool||||✔️|✔️|||
|NotMadeWho|string|||||✔️|||
|OrderPickRequestID|number||||✔️|✔️|||
|PackedBy|string||||✔️|✔️|||
|PalletID|number||||✔️|✔️|||
|PartBoxCode|string||||✔️|✔️|||
|Parts|number|||||✔️|||
|RemoveFromStock|bool||||✔️|✔️|||
|RouteCard|number|||||✔️|||
|Shift|number||||✔️|✔️|||
|ShiftDate|number||||✔️|✔️|||
|StandardHours|number|||||✔️|||
|StatusUpdatedStaffID|number|||||✔️|||
|StatusUpdatedWhen|string|||||✔️|||
|Stock_LocationID|number||||✔️|✔️|||
|StockInput|bool||||✔️|✔️|||
|StockRemovedBy|string||||✔️|✔️|||
|Time|number|||||✔️|||
|TimeProcessed|bool||||✔️|✔️|||
|TimeToPack|number|||||✔️|||
|ToolID|number||||✔️|✔️|||
|UUID|string||||✔️|✔️|✔️||
|Version|number||||✔️|✔️|||
|WhenAddedToPallet|string|||||✔️|||
|WORC|number|||||✔️|||
|WorksOrder|number||||✔️|✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Description|
|:---|:---:|:---:|:---:|:---:|
|OurPartName|ToolsEntity.ProductEntity.OurPartName|string|✔️||
|ProductEntity|ToolsEntity.ProductEntity|[Product](Product.md)|||

## Calculated Fields

|Name|Type|Read Only|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|AdviceNote|number|✔️|||
|BoxNumberColor|number|✔️|||
|BoxNumberDisplay|string|✔️|||
|BoxQuantityDisplay|string|✔️|||
|CurrentStatus|object|✔️|||
|Despatched|bool|✔️|||
|GrossWeightKg|number|✔️|||
|HasMigrationID|bool|✔️|||
|linkedBoxesQuantity|number|✔️|||
|NetWeightKg|number|✔️|||
|PackedByDisplay|string|✔️|||
|PartBox|bool|✔️|||
|partBoxSkipped|bool|✔️|||
|PartsFromOtherWorksOrders|string|✔️|||
|RouteCardColor|number|✔️|||
|StatusText|string|✔️|||
|TestProduct|[Product](Product.md)|✔️|✔️||
|toolIsRunning|bool|✔️|||
|totalBoxQuantity|number|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|CofCEntity|[CofC](CofC.md)|BoxLabelsSelection|✔️||
|LinkedBoxLabelsEntity|[BoxLabels](BoxLabels.md)|LinkedBoxLabelsSelection|✔️||
|OrderPickRequestEntity|[OrderPickRequest](OrderPickRequest.md)|BoxLabelsSelection|✔️||
|PalletEntity|[Pallet](Pallet.md)|BoxLabelsSelection|✔️||
|StatusUpdatedStaffEntity|[Staff](Staff.md)|StatusUpdatedBoxLabelsSelection|✔️||
|Stock_LocationEntity|[Stock_Location](Stock_Location.md)|BoxLabelsSelection|✔️||
|ToolsEntity|[Tools](Tools.md)|BoxLabelsSelection|✔️||
|WorksOrderEntity|[WorksOrder](WorksOrder.md)|BoxLabelsSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|LinkedBoxLabelsSelection|[BoxLabels](BoxLabels.md)|LinkedBoxLabelsEntity|✔️||