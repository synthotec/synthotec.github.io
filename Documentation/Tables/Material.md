# Material Table
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
*[Notes]: These notes have been manually added to this item for documentation purposes
*[Inverse Name]: The name of the inverse relationship from the corresponding table
*[Related Table]: The table that this relationship corresponds to
*[Local]: Function to be called on local 4D client in user space instead of remotely on server
## Fields

|Name|Type|Primary Key|Unique|Mandatory|Indexed|Exposed|Auto Filled|Notes|
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|**Unique_ID**|number|✔️|✔️||✔️|✔️|✔️||
|Archive|bool||||✔️|✔️|||
|BOM_Comment|string|||||✔️|||
|BOM_Price|number|||||✔️|||
|Calendar_Price|number|||||✔️|||
|Colour_l|number|||||✔️|||
|Current|bool||||✔️|✔️|||
|Customers Name|string||||✔️|✔️|||
|FontColour|number|||||✔️|||
|In Stock|number|||||✔️|||
|LastMigration|string|||||✔️|||
|LeadTimeDays|number|||||✔️|||
|LossPercent|number|||||✔️|||
|Manufacturer_s|string|||||✔️|||
|MaterialName|string||||✔️|✔️|||
|MigrationID|number||||✔️|✔️|||
|SafetyStockTarget|number|||||✔️|||
|SharedMaterialSource|bool|||||✔️|||
|Short Name|string|||||✔️|||
|Supplier Code|string|||||✔️|||
|Supplier Name|string|||||✔️|||
|UsageMatID|number||||✔️|✔️|||
|UsageMatID2|number||||✔️|✔️|||
|UsageMatID2Percent|number|||||✔️|||
|UsageMatID3|number||||✔️|✔️|||
|UsageMatID3Percent|number|||||✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|Unique_ID|number|||

## Calculated Fields

|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|HasMigrationID|bool|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|UsageMat1Entity|[Material](Material.md)|UsageMat1Selection|✔️||
|UsageMat2Entity|[Material](Material.md)|UsageMat2Selection|✔️||
|UsageMat3Entity|[Material](Material.md)|UsageMat3Selection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|BOMSelection|[BOM](BOM.md)|MaterialEntity|✔️||
|Customer_OrderSelection|[Customer_Order](Customer_Order.md)|MaterialEntity|✔️||
|MaterialCheckHistorySelection|[MaterialCheckHistory](MaterialCheckHistory.md)|MaterialEntity|✔️||
|MaterialStockSelection|[MaterialStock](MaterialStock.md)|MaterialEntity|✔️||
|PlanningWheelSelection|[PlanningWheel](PlanningWheel.md)|MaterialEntity|✔️||
|Product_OptionSelection|[Product_Option](Product_Option.md)|MaterialEntity|✔️||
|ProductMaterialOptionsSelection|[ProductMaterialOptions](ProductMaterialOptions.md)|MaterialEntity|✔️||
|ProductSelection|[Product](Product.md)|MaterialEntity|✔️||
|RMCSelection|[RMC](RMC.md)|MaterialEntity|✔️||
|UsageMat1Selection|[Material](Material.md)|UsageMat1Entity|✔️||
|UsageMat2Selection|[Material](Material.md)|UsageMat2Entity|✔️||
|UsageMat3Selection|[Material](Material.md)|UsageMat3Entity|✔️||
|WheelCalendarSelection|[WheelCalendar](WheelCalendar.md)|MaterialEntity|✔️||
|WorksOrderSelection|[WorksOrder](WorksOrder.md)|MaterialEntity|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Material.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationSettings()|✔️||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MaterialEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getMaterialsUsingThis()|||
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||