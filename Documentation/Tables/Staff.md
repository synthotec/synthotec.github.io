# Staff Table
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
|**StaffID**|number|✔️|✔️||✔️|✔️|✔️||
|Account4D|string|||||✔️|||
|AccountAD|string|||||✔️|||
|Archive|bool|||||✔️|||
|Code|string|||||✔️|||
|Email|string|||||✔️|||
|FirstName|string|||||✔️|||
|FobID|string|||||✔️|||
|LastName|string|||||✔️|||
|Mobile|string|||||✔️|||
|MobileKeyfob|string|||||✔️|||
|PasswordHash|string|||||✔️|||
|PersonalEmail|string|||||✔️|||
|PO_Approval|bool|||||✔️|||
|PrintAs|string|||||✔️|||
|SelfApprovalLimit|number|||||✔️|||
|SharedAccount|bool|||||✔️|||
|Stock|bool|||||✔️|||
|UserID|string|||||✔️|||
|WorkRequestEmail|string|||||✔️|||
## Aliases
|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|StaffID|number|||
## Calculated Fields
|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|FullName|string|✔️|||
## Relationships
### One to Many
|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|DB_VariablesSelection|[Settings](Settings.md)|StaffEntity|✔️||
|DeactivatedToolNoticeSelection|[ToolNotice](ToolNotice.md)|DeactivatedStaffEntity|✔️||
|PrintJobSelection|[PrintJob](PrintJob.md)|StaffEntity|✔️||
|RealTimeSensorExceptionsSelection|[RealTimeSensorExceptions](RealTimeSensorExceptions.md)|StaffEntity|✔️||
|ShiftSummarySelection|[ShiftSummary](ShiftSummary.md)|StaffEntity|✔️||
|StaffPermissionsSelection|[StaffPermissions](StaffPermissions.md)|StaffEntity|✔️||
|StatusUpdatedBoxLabelsSelection|[BoxLabels](BoxLabels.md)|StatusUpdatedStaffEntity|✔️||
|ToolNoticeSelection|[ToolNotice](ToolNotice.md)|StaffEntity|✔️||
|ToolTemperatureTargetSelection|[ToolTemperatureTarget](ToolTemperatureTarget.md)|StaffEntity|✔️||
|WorkRequestCommentsSelection|[WorkRequestComments](WorkRequestComments.md)|StaffEntity|✔️||
## Class Functions
### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Staff.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|getUsingKeyfob()|✔️||
|getCurrentUser()|✔️||
|getNonArchived()|✔️||
|newUsingEntry()|✔️||
### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/StaffEntity.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|permissionCheck()|✔️||
|copyPermissionsFrom()|✔️||