# PurchaseInfo Table
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
|**UniqueID_l**|number|✔️|✔️||✔️|✔️|✔️||
|CAPEX|number|||||✔️|||
|Cost_r|number|||||✔️|||
|Currency_s|string|||||✔️|||
|DateReceived|date|||||✔️|||
|DateRequested|date||||✔️|✔️|||
|Description_txt|string||||✔️|✔️|||
|FontSize_i|number|||||✔️|||
|FontStyle_i|number|||||✔️|||
|Invoice|string|||||✔️|||
|Invoiced|bool||||✔️|✔️|||
|InvoiceNumber|string|||||✔️|||
|NominalCode|number|||||✔️|||
|OrderNo_l|number||||✔️|✔️|||
|Price_r|number|||||✔️|||
|PriceQuantity_l|number|||||✔️|||
|Quantity_r|number|||||✔️|||
|QuantityInvoiced_r|number|||||✔️|||
|QuantityReceived_r|number|||||✔️|||
|Received|bool||||✔️|✔️|||
|Reference_s|string|||||✔️|||
|Revision|number|||||✔️|||
|SuppliesID_i|number||||✔️|✔️|||
|Unit_s|string|||||✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|UniqueID_l|number|||

## Calculated Fields

|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|OutstandingQuantity|number|✔️|||
|value|number|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|NominalCodesEntity|[NominalCodes](NominalCodes.md)|PurchaseInfoSelection|✔️||
|PurchasesEntity|[Purchases](Purchases.md)|PurchaseInfoSelection|✔️||
|SuppliesEntity|[Supplies](Supplies.md)|PurchaseInfoSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|PurchaseReceiptsSelection|[PurchaseReceipts](PurchaseReceipts.md)|PurchaseInfoEntity|✔️||
|RMCSelection|[RMC](RMC.md)|PurchaseInfoEntity|✔️||

## Class Functions

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PurchaseInfoEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|createReceipt()|✔️||