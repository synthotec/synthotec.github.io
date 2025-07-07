# RealTimeSensorExceptions Table
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
|Acknowledged|bool||||✔️|✔️|||
|Comment|string|||||✔️|||
|FirstRealTimeID|number|||||✔️|||
|LastRealTimeID|number|||||✔️|||
|RouteCards|string|||||✔️|||
|StaffID|number|||||✔️|||
|WorksOrder|number||||✔️|✔️|||
## Calculated Fields
|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|Duration|number|✔️|||
|HighestCelciusTemperature|number|✔️|||
|LowestCelciusTemperature|number|✔️|||
|PartsMade|number|✔️|||
## Relationships
### Many to One
|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|FirstRealTimeEntity|[RealTime](RealTime.md)|FirstRealTimeSensorExceptionsSelection|✔️||
|LastRealTimeEntity|[RealTime](RealTime.md)|LastRealTimeSensorExceptionsSelection|✔️||
|StaffEntity|[Staff](Staff.md)|RealTimeSensorExceptionsSelection|✔️||
|WorksOrderEntity|[WorksOrder](WorksOrder.md)|RealTimeSensorExceptionsSelection|✔️||
## Class Functions
### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeSensorExceptionsEntity.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|getRealTimeSelection()|✔️||
|getTemperatureSensors()|✔️||
|sendEmail()|||
### [Selection Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeSensorExceptionsSelection.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|acknowledge()|✔️||