---
layout: default
title: Customer
parent: Tables
---
# Customer Table
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
|**Customer_Code**|string|✔️|✔️||✔️|✔️|||
|Acknow Contact|string|||||✔️|||
|Acknowledgement|bool|||||✔️|||
|Archive|bool||||✔️|✔️|||
|BoxesPerPallet|number|||||✔️|||
|CofCRequired_b|bool|||||✔️|||
|Consignment|bool||||✔️|✔️|||
|ConsignmentLocationID|number||||✔️|✔️|||
|Cust Addr1|string|||||✔️|||
|Cust Addr2|string|||||✔️|||
|Cust Addr3|string||||✔️|✔️|||
|Cust Addr4|string|||||✔️|||
|Cust Contact1|string|||||✔️|||
|Cust Cum Ord|number|||||✔️|||
|Cust Fax|string|||||✔️|||
|Cust Inv Date|date|||||✔️|||
|Cust Label1|string|||||✔️|||
|Cust Label2|string|||||✔️|||
|Cust label3|string|||||✔️|||
|Cust Name|string|||||✔️|||
|Cust Notes|string|||||✔️|||
|Cust Phone1|string|||||✔️|||
|Cust Postcode|string|||||✔️|||
|CustContact2|string|||||✔️|||
|CustContact3|string|||||✔️|||
|CustContact4|string|||||✔️|||
|CustContact5|string|||||✔️|||
|CustContact6|string|||||✔️|||
|CustPhone2|string|||||✔️|||
|CustPhone3|string|||||✔️|||
|CustPhone4|string|||||✔️|||
|CustPhone5|string|||||✔️|||
|CustPhone6|string|||||✔️|||
|CustPosition1|string|||||✔️|||
|CustPosition2|string|||||✔️|||
|CustPosition3|string|||||✔️|||
|CustPosition4|string|||||✔️|||
|CustPosition5|string|||||✔️|||
|CustPosition6|string|||||✔️|||
|DeliveryAddress_txt|string|||||✔️|||
|DeliveryDays|number|||||✔️|||
|Email1|string|||||✔️|||
|Email2|string|||||✔️|||
|Email3|string|||||✔️|||
|Email4|string|||||✔️|||
|Email5|string|||||✔️|||
|Email6|string|||||✔️|||
|LastMigration|string|||||✔️|||
|MigrationID|string||||✔️|✔️|||
|NtnSnrLocationCode|string||||✔️|✔️|||
|OrderEmail|string|||||✔️|||
|PalletTransportCost|number|||||✔️|||
|RequiresMaterialCofA|bool|||||✔️|||
|SupplierCode|string|||||✔️|||
|TransportComment|string|||||✔️|||
|TransportInstructionFileID|number|||||✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|Customer_Code|string|||

## Calculated Fields

|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|HasMigrationID|bool|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|Stock_LocationEntity|[Stock_Location](Stock_Location.md)|CustomerSelection|✔️||
|TransportInstructionFileEntity|[File](File.md)|CustomerSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|ApprovalsSelection|[Approvals](Approvals.md)|CustomerEntity|✔️||
|BOMSelection|[BOM](BOM.md)|CustomerEntity|✔️||
|Customer_OrderSelection|[Customer_Order](Customer_Order.md)|CustomerEntity|✔️||
|CustomerContactsSelection|[CustomerContacts](CustomerContacts.md)|CustomerEntity|✔️||
|PickRequestSelection|[PickRequest](PickRequest.md)|CustomerEntity|✔️||
|Product_OptionSelection|[Product_Option](Product_Option.md)|CustomerEntity|✔️||
|ProductPackagingSelection|[ProductPackaging](ProductPackaging.md)|CustomerEntity|✔️||
|WorksOrderSelection|[WorksOrder](WorksOrder.md)|CustomerEntity|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationSettings()|✔️||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CustomerEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||