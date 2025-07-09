---
layout: default
title: NonConformance
parent: Tables
---
# NonConformance Table
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
|**ID**|number|✔️|✔️||✔️|✔️|✔️||
|ActionNonDetection_Date|date|||||✔️|||
|ActionNonDetection_Signed|string|||||✔️|||
|ActionNonDetection_txt|string|||||✔️|||
|CauseofConcern|string|||||✔️|||
|CauseOfNonDetection_txt|string|||||✔️|||
|Completed_No|bool|||||✔️|||
|Completed_Yes|bool|||||✔️|||
|ConcernRecdBy|string|||||✔️|||
|ConcernRecdDate|date|||||✔️|||
|CreateWorkRequest|bool|||||✔️|||
|Customer|string|||||✔️|||
|Date|date|||||✔️|||
|Effective_Action|string|||||✔️|||
|Effective_Date|date|||||✔️|||
|Effective_Signed|string|||||✔️|||
|Field_44|string|||||✔️|||
|FMEA|string|||||✔️|||
|FMEA_Date|date|||||✔️|||
|FMEA_Signed|string|||||✔️|||
|Is_A_PQI|bool||||✔️|✔️|||
|NatureOfConcern|string|||||✔️|||
|NoofExternalPQI|number|||||✔️|||
|NoofInternalPQI|number|||||✔️|||
|Part_IssueLevel|string|||||✔️|||
|QualityImprove_Action|string|||||✔️|||
|QualityImprove_Date|date|||||✔️|||
|QualityImprove_Sign|string|||||✔️|||
|Recurrence_Action|string|||||✔️|||
|Recurrence_Date|date|||||✔️|||
|Recurrence_Signed|string|||||✔️|||
|Reference_No|string||✔️||✔️|✔️|||
|Reply_Due|string|||||✔️|||
|Responded_On|date|||||✔️|||
|Stock_ActionTaken|string|||||✔️|||
|Stock_Date|date|||||✔️|||
|Stock_Location|string|||||✔️|||
|Stock_Quantity|number|||||✔️|||
|Stock_Signed|string|||||✔️|||
|Stock_Status|string|||||✔️|||
|Tool_ID|number||||✔️|✔️|||
|Type_Of_Concern|string|||||✔️|||
|WIP_ActionTaken|string|||||✔️|||
|WIP_Date|date|||||✔️|||
|WIP_Location|string|||||✔️|||
|WIP_Quantity|number|||||✔️|||
|WIP_Signed|string|||||✔️|||
|WIP_Status|string|||||✔️|||
|Works_Order_No|number|||||✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Description|
|:---|:---:|:---:|:---:|:---:|
|ToolsEntity|[Tools](Tools.md)|NonConformanceSelection|✔️||