---
layout: default
title: RealTimeMachines
parent: Tables
---
# RealTimeMachines Table
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
|**Machine**|number|✔️|✔️||✔️|✔️|||
|AutoStatus|bool|||||✔️|||
|Availability|number|||||✔️|||
|AwaitingSetter|number|||||✔️|||
|Battery|number|||||✔️|||
|Cycle|number|||||✔️|||
|DownReason|number|||||✔️|||
|Enabled|bool||||✔️|✔️|||
|LastActivity|string|||||✔️|||
|LastAudit|string|||||✔️|||
|LastCycleSensorData|object|||||✔️|||
|LastCycleTime|number|||||✔️|||
|LastPulse|string|||||✔️|||
|MadeQty|number|||||✔️|||
|MouldClosed|bool|||||✔️|||
|MouldStatus|string|||||✔️|||
|NextJobID|number|||||✔️|||
|NoWorksOrderEmailSent|bool|||||✔️|||
|Performance|number|||||✔️|||
|PowerStatus|bool|||||✔️|||
|Quality|number|||||✔️|||
|RealMade|number|||||✔️|||
|RequiresRecalculation|bool|||||✔️|||
|Robot|bool|||||✔️|||
|SlowStatus|bool|||||✔️|||
|StopReason|string|||||✔️|||
|TemperatureSensorException|bool|||||✔️|||
|TemperatureSensors|object|||||✔️|||
|TimeLeft|number|||||✔️|||
|TimeStartedNonRobot|string|||||✔️|||
|UpTime|string|||||✔️|||
|WinVer|string|||||✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|Machine|number|||

## Calculated Fields

|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|AssignedTemperatureSensorsPresent|bool|✔️|||
|Changing|bool|✔️|||
|TemperatureSensorsInstalled|bool|✔️|||
|UniChar|string|✔️|||
|WorksOrder|number|✔️|||
|WorksOrderEntity|[WorksOrder](WorksOrder.md)|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|DownReasonsEntity|[DownReasons](DownReasons.md)|RealTimeMachinesSelection|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeMachines.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|getByMachine()|||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeMachinesEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|checkTempZoneExists()|||