﻿---
layout: default
title: ToolTemperatureTarget
parent: Tables
---
# ToolTemperatureTarget Table
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
|LastUpdated|string|||||✔️|||
|Max|number|||||✔️|||
|MigrationID|number|||||✔️|||
|Min|number|||||✔️|||
|StaffID|number|||||✔️|||
|Target|number|||||✔️|||
|ToolID|number||||✔️|✔️|||
|ZoneID|number||||✔️|✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Description|
|:---|:---:|:---:|:---:|:---:|
|ZoneName|ToolTemperatureZoneEntity.Name|string|✔️||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|StaffEntity|[Staff](Staff.md)|ToolTemperatureTargetSelection|✔️||
|ToolsEntity|[Tools](Tools.md)|ToolTemperatureTargetSelection|✔️||
|ToolTemperatureZoneEntity|[ToolTemperatureZone](ToolTemperatureZone.md)|ToolTemperatureTargetSelection|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureTarget.4dm)

|Name|Local|Description|
|:---|:---:|:---:|
|getByWorksOrder()|||
|getMigrationSettings()|✔️||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureTargetEntity.4dm)

|Name|Local|Description|
|:---|:---:|:---:|
|SetTargetValues()|✔️||
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||

### [Selection Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureTargetSelection.4dm)

|Name|Local|Description|
|:---|:---:|:---:|
|CheckInRange()|||
|CheckTargetsSet()|||