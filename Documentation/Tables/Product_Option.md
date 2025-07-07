# Product_Option Table
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
|**ID**|number|✔️|✔️||✔️|✔️|✔️||
|Batch Quantity|number|||||✔️|||
|Comments|string|||||✔️|||
|Con_LastReceived|date|||||✔️|||
|Consignment|bool|||||✔️|||
|ConsignmentMax|number|||||✔️|||
|ConsignmentMin|number|||||✔️|||
|Currency|string|||||✔️|||
|CurrentConsignmentOrder|string|||||✔️|||
|Customer Code|string||||✔️|✔️|||
|CustomerReference|string|||||✔️|||
|Deconsigned_Stock|number|||||✔️|||
|DefaultOrderNumber|string|||||✔️|||
|DeliveryCost|number|||||✔️|||
|INCOTERM|string|||||✔️|||
|Material Name|string||||✔️|✔️|||
|Material_ID|number||||✔️|✔️|||
|MigrationID|number|||||✔️|||
|Modified_Date|date|||||✔️|||
|MOQ|number|||||✔️|||
|MOV|number|||||✔️|||
|Part No|string||||✔️|✔️|||
|Price|number||||✔️|✔️|||
|PriceQuantity|number|||||✔️|||
|Product ID|number||||✔️|✔️|||
|SSLOffsetDays|number|||||✔️|||
|SSLOverride|number|||||✔️|||
|Tool ID|number|||||✔️|||
|Tool No|string||||✔️|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|CustomerEntity|[Customer](Customer.md)|Product_OptionSelection|✔️||
|MaterialEntity|[Material](Material.md)|Product_OptionSelection|✔️||
|ProductEntity|[Product](Product.md)|Product_OptionSelection|✔️||
|ToolsEntity|[Tools](Tools.md)|Product_OptionSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|Customer_OrderSelection|[Customer_Order](Customer_Order.md)|Product_OptionEntity|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Product_Option.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationSettings()|✔️||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Product_OptionEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||