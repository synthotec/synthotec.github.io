# Tools Table
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
|**Tool_ID**|number|✔️|✔️||✔️|✔️|✔️||
|Additional_text|string|||||✔️|||
|Additional_text_4_label|string|||||✔️|||
|AlternatingLayerQuantA|number|||||✔️|||
|AlternatingLayerQuantB|number|||||✔️|||
|Amber|bool|||||✔️|||
|AmberCheckPercent|number|||||✔️|||
|AmberManual|bool|||||✔️|||
|AmberManualWhen|date|||||✔️|||
|AmberManualWho|string|||||✔️|||
|AmberPQITriggered|bool|||||✔️|||
|AmberTriggerTime|string|||||✔️|||
|Approved|bool|||||✔️|||
|AQP|bool|||||✔️|||
|Archive|bool||||✔️|✔️|||
|BagSealingMethod|string|||||✔️|||
|Box_Per_Pallet|number|||||✔️|||
|Boxes_Per_M_Pallet|number|||||✔️|||
|Cages_per_Mandrell|number|||||✔️|||
|Concess End Dat|date|||||✔️|||
|Concession No|string|||||✔️|||
|Conditioned|bool|||||✔️|||
|Customer Label|string|||||✔️|||
|CycleTimeSecs|number|||||✔️|||
|DataMatrix|bool|||||✔️|||
|Date Created|date|||||✔️|||
|DateChanged|date|||||✔️|||
|DateToolDueBack_d|date|||||✔️|||
|Dry_Weight|number|||||✔️|||
|DryWeightText|string|||||✔️|||
|ExtraPackInfo|string|||||✔️|||
|ExtraSideLabel|bool|||||✔️|||
|Final_Customer|string|||||✔️|||
|ForeCast2015|number|||||✔️|||
|ForeCast2015Update|date|||||✔️|||
|Grey box Quan|number|||||✔️|||
|HotHalfBooked|bool||||✔️|✔️|||
|HotHalfID|number||||✔️|✔️|||
|identifier_address|string|||||✔️|||
|If Concess by N|bool|||||✔️|||
|If on Concess|bool|||||✔️|||
|Impressions|number|||||✔️|||
|Initial Cust|string|||||✔️|||
|IsHandLoaded|bool|||||✔️|||
|IsToolOffsite_b|bool|||||✔️|||
|Kit_ProductID|string|||||✔️|||
|Kit_Quantity|number|||||✔️|||
|LabelChoice_s|string|||||✔️|||
|LabelOrigin|bool|||||✔️|||
|LargeSide|bool|||||✔️|||
|Location|string|||||✔️|||
|LogisticsPrefix|string|||||✔️|||
|Machine_Type|string|||||✔️|||
|Main Tool|bool|||||✔️|||
|MaintenanceCycleTrigger|number|||||✔️|||
|Mandrel_OD|number|||||✔️|||
|Mandrells_per_Pallet|number|||||✔️|||
|MigrationID|number||||✔️|✔️|||
|NewCalcedPartWeight|number|||||✔️|||
|NextUniqueIDLogistics_l|number|||||✔️|||
|NextUniqueLabelID_l|number|||||✔️|||
|No Concess Supp|number|||||✔️|||
|No_metalpallets_per_box|number|||||✔️|||
|NotifyQuality|bool|||||✔️|||
|NotifyReason|string|||||✔️|||
|Nozzle|string|||||✔️|||
|NumOfLayers|number|||||✔️|||
|NumOfRows|number|||||✔️|||
|OddLayerQuantity|number|||||✔️|||
|OperatorRequired|bool|||||✔️|||
|PackagingInstructionIssueDate|date|||||✔️|||
|PackagingInstructionIssueLevel|string|||||✔️|||
|PackagingInstructionIssueName|string|||||✔️|||
|Packed_Per_Hour|number|||||✔️|||
|PackedInColumns|bool|||||✔️|||
|Packing Box|string|||||✔️|||
|packrange_max|number|||||✔️|||
|Pallet_Pic|image|||||✔️|||
|Pallet_Type_m|string|||||✔️|||
|PartNo|string||||✔️|✔️|||
|PartWtGrams|number|||||✔️|||
|PicBlob|blob|||||✔️|||
|PicBlobTxt|string|||||✔️|||
|Picture|image|||||✔️|||
|PlanningWheelCycle|number|||||✔️|||
|PlanningWheelHours|number|||||✔️|||
|Prodn Quan Max|number|||||✔️|||
|Prodn Quan Min|number|||||✔️|||
|ProductID|number||||✔️|✔️|||
|Production_Mandrell|string|||||✔️|||
|ProductionHoldObject|object|||||✔️|||
|ProductName|string|||||✔️|||
|QRCode|bool|||||✔️|||
|QRtype|number|||||✔️|||
|qty_delivered_flag|bool|||||✔️|||
|qty_pricechange|number|||||✔️|||
|RC_Additional_Seq|bool|||||✔️|||
|RC_Barcode|bool|||||✔️|||
|RC_Sub_Sequence|number|||||✔️|||
|RCText|string|||||✔️|||
|ReasonToolOffsite_txt|string|||||✔️|||
|Regrind|bool|||||✔️|||
|Regrind_MaxPercent|number|||||✔️|||
|RegrindComments|string|||||✔️|||
|RequiresChecking|bool|||||✔️|||
|Robot_Prg_No|string|||||✔️|||
|RobotHeads|string|||||✔️|||
|RunnerWtGrams|number|||||✔️|||
|RunsSinceApproval|number|||||✔️|||
|ScalesFixedQuant|number|||||✔️|||
|Separator|number|||||✔️|||
|Setup_Sheet|bool|||||✔️|||
|Short Name|string|||||✔️|||
|ShortName|string||||✔️|✔️|||
|SmallSide|bool|||||✔️|||
|StatusUpdated|string|||||✔️|||
|TemperatureTargetMax|number|||||✔️|||
|TemperatureTargetMin|number|||||✔️|||
|TimePerPallet|number|||||✔️|||
|Tool Mod|string|||||✔️|||
|Tool_No|string||✔️||✔️|✔️|||
|Tool_Notes|string|||||✔️|||
|ToolDueDate|date|||||✔️|||
|ToolNoticeObject|object|||||✔️|||
|ToolOffsite|bool|||||✔️|||
|ToolReady|bool|||||✔️|||
|Total No Conces|number|||||✔️|||
|two_boxnos|bool||||✔️|✔️|||
|Type|number|||||✔️|||
|UsageWarningDays|number|||||✔️|||
|UseAddressLabels_b|bool|||||✔️|||
|UseBagLabel_b|bool|||||✔️|||
|UseExtraID_b|bool|||||✔️|||
|UseLogisticslabel_b|bool|||||✔️|||
|UseUniqueIDLabels_b|bool|||||✔️|||
|Weight_kitlabel|number|||||✔️|||
|x2_uniqueIDlabels|bool|||||✔️|||
|x3_sequence_packsheet|bool|||||✔️|||
|x4_sequence_packsheet|bool|||||✔️|||
## Aliases
|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|Tool_ID|number|||
## Calculated Fields
|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|NextToolChangeText|string|✔️|||
|SensorExceptionsCount|number|✔️|✔️||
## Relationships
### Many to One
|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|HotHalfEntity|[HotHalfs](HotHalfs.md)|ToolsSelection|✔️||
|ProductEntity|[Product](Product.md)|ToolsSelection|✔️||
### One to Many
|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|ApprovalsSelection|[Approvals](Approvals.md)|ToolsEntity|✔️||
|BoxLabelsSelection|[BoxLabels](BoxLabels.md)|ToolsEntity|✔️||
|NonConformanceSelection|[NonConformance](NonConformance.md)|ToolsEntity|✔️||
|PlanningWheelSelection|[PlanningWheel](PlanningWheel.md)|ToolsEntity|✔️||
|Product_OptionSelection|[Product_Option](Product_Option.md)|ToolsEntity|✔️||
|ToolDocumentSelection|[ToolDocument](ToolDocument.md)|ToolsEntity|✔️||
|ToolLogSelection|[ToolLog](ToolLog.md)|ToolsEntity|✔️||
|ToolMaintenanceLogSelection|[ToolMaintenanceLog](ToolMaintenanceLog.md)|ToolsEntity|✔️||
|ToolNoticeSelection|[ToolNotice](ToolNotice.md)|ToolsEntity|✔️||
|ToolTemperatureTargetSelection|[ToolTemperatureTarget](ToolTemperatureTarget.md)|ToolsEntity|✔️||
|WorkRequestsSelection|[WorkRequests](WorkRequests.md)|ToolsEntity|✔️||
|WorksOrderSelection|[WorksOrder](WorksOrder.md)|ToolsEntity|✔️||
## Class Functions
### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Tools.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationSettings()|✔️||
|createForProduct()|✔️||
### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolsEntity.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||