---
layout: default
title: Pallet
parent: Tables
---
# Pallet Table
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
|**ID**|number|✔️|✔️|✔️|✔️|✔️|✔️||
|AdviceNote|number|||||✔️|||
|CofCID|number||||✔️|✔️|||
|Completed|bool||||✔️|✔️|||
|Created|date|||||✔️|||
|CreatedBy|string|||||✔️|||
|CreationTime|number|||||✔️|||
|Despatched|bool||||✔️|✔️|||
|LastMigration|string|||||✔️|||
|LocatedBy|string|||||✔️|||
|Location|number|||||✔️|||
|LocationID|string||||✔️|✔️|||
|MigrationID|number|||||✔️|||
|NewSystem|bool||||✔️|✔️|||
|OrderID|number|||||✔️|||
|OrderPickRequestID|number||||✔️|✔️|||
|Printed|bool||||✔️|✔️|||
|PrintedBy|string|||||✔️|||
|ProductID|number||||✔️|✔️|||
|Transfer|bool|||||✔️|||
|UUID|string||✔️||✔️|✔️|✔️||
|Verified|bool||||✔️|✔️|||
|VerifiedBy|string|||||✔️|||
|Version|number||||✔️|✔️|||
|WO1|number|||||✔️|||
|WO1Qty|number|||||✔️|||
|WO2|number|||||✔️|||
|WO2Qty|number|||||✔️|||

## Calculated Fields

|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|GrossWeightKg|number|✔️|||
|HasMigrationID|bool|✔️|||
|NetWeightKg|number|✔️|||
|QRObject|object|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|CofCEntity|[CofC](CofC.md)|PalletSelection|✔️||
|LocationEntity|[Location](Location.md)|PalletSelection|✔️||
|OrderPickRequestEntity|[OrderPickRequest](OrderPickRequest.md)|PalletSelection|✔️||
|ProductEntity|[Product](Product.md)|PalletSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|BoxLabelsSelection|[BoxLabels](BoxLabels.md)|PalletEntity|✔️||
|PrintJobSelection|[PrintJob](PrintJob.md)|PalletEntity|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Pallet.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationSettings()|✔️||
|getAvailableToPick()|✔️||
|getUsingScanner()|||
|Create()|||
|Verify()|||
|Print()|||
|Delete()|||
|restLoadPalletList()|||
|restAddToPallet()|||
|restCompletePallet()|||
|restPrintPallet()|✔️||
|restVerifyPallet()|||
|restLocatePallet()|||
|restDeletePallet()|||
|restReassignLocation()|||
|restLoadPallet()|||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PalletEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|createPrintJob()|||
|getWorksOrderCollection()|||
|getTotalQuantity()|||
|getTotalBoxes()|||
|generateQR()|✔️||
|getStockListBoxObject()|✔️||
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||
|transfer()|✔️||

### [Selection Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PalletSelection.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getAvailable()|✔️||