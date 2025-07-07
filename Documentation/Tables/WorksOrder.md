# WorksOrder Table
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
|**Works_Order_No**|number|✔️|✔️||✔️|✔️|✔️||
|AmberQuarantine|bool|||||✔️|||
|AutomaticStock|bool||||✔️|✔️|||
|Barcodenum_labelid|string|||||✔️|||
|Barcodenum_Part|string|||||✔️|||
|Barcodenum_quantity|string|||||✔️|||
|Barcodenum_supplierid|string|||||✔️|||
|Barcodenum_worksorder|string|||||✔️|||
|Barcodepicture_labelid|string|||||✔️|||
|Barcodepicture_part|string|||||✔️|||
|Barcodepicture_quantity|string|||||✔️|||
|Barcodepicture_supplierid|string|||||✔️|||
|Barcodepicture_workorder|string|||||✔️|||
|Calculated_Scrap|number|||||✔️|||
|Completed_Date|date|||||✔️|||
|Current_Production_Quantity|number|||||✔️|||
|Customer_Code|string||||✔️|✔️|||
|Cycle_Flag|bool|||||✔️|||
|Cycle_Time|number|||||✔️|||
|Date_Created|date|||||✔️|||
|DrawingNo|string|||||✔️|||
|Dry_Weight|number|||||✔️|||
|Entered_Parts_Scrap|number|||||✔️|||
|Fin_Initals|string|||||✔️|||
|Fin_Packed_Date|date|||||✔️|||
|FinishTime|number|||||✔️|||
|FirstOffComments|string|||||✔️|||
|FirstOffCompleted|bool|||||✔️|||
|FirstOffWeightsChecked|bool|||||✔️|||
|FixedDate|date|||||✔️|||
|Impressions|number|||||✔️|||
|Is_a_Trial|bool|||||✔️|||
|Issue_No|string||||✔️|✔️|||
|Label_Text|string|||||✔️|||
|Labels|bool|||||✔️|||
|LastMigration|string|||||✔️|||
|LastProcessedRealTimeID|number|||||✔️|||
|Machine_Completed|bool||||✔️|✔️|||
|Machine_No|number||||✔️|✔️|||
|Machine_Started|bool||||✔️|✔️|||
|MaterialCheckComment|string|||||✔️|||
|MaterialCheckedBy|string|||||✔️|||
|MaterialID|number||||✔️|✔️|||
|MaterialName|string|||||✔️|||
|MigrationID|number||||✔️|✔️|||
|NewSystem|bool||||✔️|✔️|||
|No_In_Stock|number||||✔️|✔️|||
|Notes|string|||||✔️|||
|OEEgenerated|bool||||✔️|✔️|||
|Packing_Box_No|number|||||✔️|||
|Packing_Completed|bool||||✔️|✔️|||
|PackingSheetPrinted|bool|||||✔️|||
|Part_No|string||||✔️|✔️|||
|Part_Weight|number|||||✔️|||
|Parts_Delivered|number|||||✔️|||
|Parts_Packed|number|||||✔️|||
|PlannedMaterialID|number|||||✔️|||
|ProductID_l|number||||✔️|✔️|||
|Production_Chart_DateSent|date|||||✔️|||
|Production_Chart_Status|bool|||||✔️|||
|Production_Target|number|||||✔️|||
|Quantity_Manufactured|number|||||✔️|||
|Quarantine_Finished_Stock|number|||||✔️|||
|Quarantine_Returned_Stock_l|number|||||✔️|||
|Quarantine_UnpackedWIP_Stock|number|||||✔️|||
|Quarantined_b|bool|||||✔️|||
|QuarantineReason|string|||||✔️|||
|Raised_Job_Card|bool||||✔️|✔️|||
|Regrind|bool|||||✔️|||
|ReturnsScrap_l|number|||||✔️|||
|rFtime|number|||||✔️|||
|RMC_Nos|string|||||✔️|||
|Robot|bool||||✔️|✔️|||
|RouteCards|bool|||||✔️|||
|rStime|number|||||✔️|||
|Runner_Weight|number|||||✔️|||
|SequencedNo|number|||||✔️|||
|SetDate|date|||||✔️|||
|Start_Date|date|||||✔️|||
|StartTime|number|||||✔️|||
|Tool_No|string|||||✔️|||
|ToolID|number||||✔️|✔️|||
|UpdatePartsMadeDate|date|||||✔️|||
|Weight_Initals|string|||||✔️|||
|WorkInProgress|number|||||✔️|||
## Aliases
|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ID|Works_Order_No|number|||
## Calculated Fields
|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|AvailableStock|number|✔️|||
|ExS1Stock|number|✔️|||
|HasMigrationID|bool|✔️|||
|IsOpen|bool|✔️|||
|IsRunning|bool|✔️|||
|WIP|number|✔️|||
## Relationships
### Many to One
|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|CustomerEntity|[Customer](Customer.md)|WorksOrderSelection|✔️||
|MaterialEntity|[Material](Material.md)|WorksOrderSelection|✔️||
|ProductEntity|[Product](Product.md)|WorksOrderSelection|✔️||
|ToolsEntity|[Tools](Tools.md)|WorksOrderSelection|✔️||
### One to Many
|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|BoxLabelsSelection|[BoxLabels](BoxLabels.md)|WorksOrderEntity|✔️||
|CofCSelection|[CofC](CofC.md)|WorksOrderEntity|✔️||
|Finished_StockSelection|[Finished_Stock](Finished_Stock.md)|WorksOrderEntity|✔️||
|MaterialCheckHistorySelection|[MaterialCheckHistory](MaterialCheckHistory.md)|WorksOrderEntity|✔️||
|ProductReturnWorksOrderSelection|[ProductReturnWorksOrder](ProductReturnWorksOrder.md)|WorksOrderEntity|✔️||
|ProductStockTakeSelection|[ProductStockTake](ProductStockTake.md)|WorksOrderEntity|✔️||
|RealTimeSelection|[RealTime](RealTime.md)|WorksOrderEntity|✔️||
|RealTimeSensorExceptionsSelection|[RealTimeSensorExceptions](RealTimeSensorExceptions.md)|WorksOrderEntity|✔️||
|RTSUMSelection|[RTSUM](RTSUM.md)|WorksOrderEntity|✔️||
|ScrapSelection|[Scrap](Scrap.md)|WorksOrderEntity|✔️||
|ShiftSummaryDetailSelection|[ShiftSummaryDetail](ShiftSummaryDetail.md)|WorksOrderEntity|✔️||
|Stock_MovementSelection|[Stock_Movement](Stock_Movement.md)|WorksOrderEntity|✔️||
|ToolNoticeWorksOrderSelection|[ToolNoticeWorksOrder](ToolNoticeWorksOrder.md)|WorksOrderEntity|✔️||
|WheelCalendarSelection|[WheelCalendar](WheelCalendar.md)|WorksOrderEntity|✔️||
## Class Functions
### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/WorksOrder.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|getMigrationSettings()|✔️||
### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/WorksOrderEntity.4dm)
|Name|Local|Notes|
|:---|:---:|:---:|
|setQuantityMade()|✔️||
|getQuantityMade()|✔️||
|getQuantityPacked()|✔️||
|getQuantityScrapped()|✔️||
|calculateProcessScrap()|✔️||
|getMigrationRules()|✔️||
|syncMigrationSelections()|✔️||