# CofC Table
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
|**Cert_Of_Conformance_No**|number|✔️|✔️||✔️|✔️|✔️||
|Advice_Note_No|number||||✔️|✔️|||
|Batch_No|string|||||✔️|||
|CofC_Report|bool||||✔️|✔️|||
|Created_Date|date|||||✔️|||
|Customer_Code|string||||✔️|✔️|||
|Customer_Order_No|string|||||✔️|||
|Date_Int|number||||✔️|✔️|||
|DeliveredDate_d|date|||||✔️|||
|Delivery_Method_s|string|||||✔️|||
|Delivery_Quantity|number|||||✔️|||
|Invoice_Report|bool||||✔️|✔️|||
|LocationID_l|number|||||✔️|||
|LocationName_s|string|||||✔️|||
|loose|string|||||✔️|||
|MovementCofC|bool||||✔️|✔️|||
|Number_In_Box|number|||||✔️|||
|Nunber_Of_Boxes|number|||||✔️|||
|Order_Completed|bool|||||✔️|||
|Part No|string||||✔️|✔️|||
|Petes No|number||||✔️|✔️|||
|Price|number|||||✔️|||
|ProductID_l|number||||✔️|✔️|||
|Quantity_Loose|number|||||✔️|||
|RMC_Nos|string|||||✔️|||
|Works_Order_No|number||||✔️|✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|Cert_Of_Conformance_No|number|||
|Product_OptionID|Customer_OrderEntity.Product_OptionID|number|✔️||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|Advice_NoteEntity|[Advice_Note](Advice_Note.md)|CofCSelection|✔️||
|Customer_OrderEntity|[Customer_Order](Customer_Order.md)|CofCSelection|✔️||
|ProductEntity|[Product](Product.md)|CofCSelection|✔️||
|Stock_LocationEntity|[Stock_Location](Stock_Location.md)|CofCSelection|✔️||
|WorksOrderEntity|[WorksOrder](WorksOrder.md)|CofCSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|BoxLabelsSelection|[BoxLabels](BoxLabels.md)|CofCEntity|✔️||
|PalletSelection|[Pallet](Pallet.md)|CofCEntity|✔️||

## Class Functions

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CofCEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|cancel()|||