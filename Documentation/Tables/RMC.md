---
layout: default
title: RMC
parent: Tables
---
# RMC Table
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
|**RMCNo_l**|number|✔️|✔️||✔️|✔️|✔️||
|BatchNo_s|string|||||✔️|||
|CofA_BLOB|blob|||||✔️|||
|CofA_Filename|string|||||✔️|||
|CofA_Requested|date|||||✔️|||
|MaterialID_l|number||||✔️|✔️|||
|Name_s|string|||||✔️|||
|OrderNo_l|number|||||✔️|||
|PurchaseInfoID|number||||✔️|✔️|||
|Quantity_l|number|||||✔️|||
|Remarks_s|string|||||✔️|||
|RMCDate_d|date||||✔️|✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|RMCNo_l|number|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|MaterialEntity|[Material](Material.md)|RMCSelection|✔️||
|PurchaseInfoEntity|[PurchaseInfo](PurchaseInfo.md)|RMCSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|MaterialCheckHistorySelection1|[MaterialCheckHistory](MaterialCheckHistory.md)|RMCEntity1|✔️||
|MaterialCheckHistorySelection2|[MaterialCheckHistory](MaterialCheckHistory.md)|RMCEntity2|✔️||
|MaterialCheckHistorySelection3|[MaterialCheckHistory](MaterialCheckHistory.md)|RMCEntity3|✔️||
|MaterialStockSelection|[MaterialStock](MaterialStock.md)|RMCEntity|✔️||
|MaterialStockTakeSelection|[MaterialStockTake](MaterialStockTake.md)|RMCEntity|✔️||
|PurchaseReceiptsSelection|[PurchaseReceipts](PurchaseReceipts.md)|RMCEntity|✔️||

## Class Functions

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RMCEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|delete()|✔️||
|requestCertificate()|✔️||