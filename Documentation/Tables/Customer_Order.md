# Customer_Order Table
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
|**Petes_No**|number|✔️|✔️||✔️|✔️|✔️||
|Acknowledged|bool|||||✔️|||
|Ammeded_Date|date||||✔️|✔️|||
|Batch_No|string|||||✔️|||
|BoxesMonthAfter|number|||||✔️|||
|CalculatedDespatchDate|date|||||✔️|||
|Completed|bool||||✔️|✔️|||
|Confirmed|bool||||✔️|✔️|||
|ConfirmedDate|date|||||✔️|||
|ConfirmedDue|date|||||✔️|||
|ConOrderDummy|bool|||||✔️|||
|ConsignmentDummy|bool|||||✔️|||
|ConsignmentOTIFCheck|bool|||||✔️|||
|Cumulative|number|||||✔️|||
|Cust Part No|string|||||✔️|||
|Customer_Code|string||||✔️|✔️|||
|Customer_Delivery_Date|date||||✔️|✔️|||
|Customer_Order_Date|date|||||✔️|||
|Customer_Order_No|string||||✔️|✔️|||
|Date_Received|date|||||✔️|||
|DateReviewed|date|||||✔️|||
|DaysLate|number|||||✔️|||
|Delivered_Value|number|||||✔️|||
|FinWheelID|number||||✔️|✔️|||
|FinWheelMC|number|||||✔️|||
|Forecast|bool||||✔️|✔️|||
|FutureYearForecast|bool||||✔️|✔️|||
|Invoiced|bool|||||✔️|||
|Is_a_Trial|bool|||||✔️|||
|Is_New_Order|bool|||||✔️|||
|Is_On_hold|bool|||||✔️|||
|Is_Replacement|bool|||||✔️|||
|Issue_Date|date|||||✔️|||
|Issue_No|string|||||✔️|||
|MakeOrder|number||||✔️|✔️|||
|Material_CName|string|||||✔️|||
|Material_ID|number||||✔️|✔️|||
|MaterialOurName|string|||||✔️|||
|MCPlanned|number|||||✔️|||
|Nominal_Sale|number|||||✔️|||
|NSKCurrentSYNStock|number|||||✔️|||
|NSKDelivered|number|||||✔️|||
|NSKUndelivered|number|||||✔️|||
|Order_Price|number|||||✔️|||
|OrderNotes|string|||||✔️|||
|OTIF|bool|||||✔️|||
|OTIF_Comments|string|||||✔️|||
|OTIF_Shortfall|number|||||✔️|||
|Our_Delivery_Date|date||||✔️|✔️|||
|Part_Delivery|bool|||||✔️|||
|Part_No|string||||✔️|✔️|||
|Price_Quantity|number|||||✔️|||
|ProcurementProgramOrder|bool||||✔️|✔️|||
|Product_ID|number||||✔️|✔️|||
|Product_OptionID|number||||✔️|✔️|||
|ProductionReadyDate|date|||||✔️|||
|QtyMonthAfter|number|||||✔️|||
|Quantity_Delivered|number|||||✔️|||
|Quantity_Ordered|number|||||✔️|||
|Quantity_Required|number|||||✔️|||
|Ready_To_Delete|bool||||✔️|✔️|||
|ReadyOnDate|number|||||✔️|||
|Reviewed|bool||||✔️|✔️|||
|ReviewedReadyDate|date|||||✔️|||
|SIMUsageOrder|bool|||||✔️|||
|Status|string|||||✔️|||
|Suggested|number|||||✔️|||
|Tool_ID|number|||||✔️|||
|Tool_No|string|||||✔️|||

## Aliases

|Name|Alias Path|Type|Read Only|Notes|
|:---|:---:|:---:|:---:|:---:|
|ConfirmedArrivalDate|ConfirmedDue|date|||
|ConfirmedDespatchDate|ReviewedReadyDate|date|||
|ID|Petes_No|number|||

## Calculated Fields

|Name|Type|Read Only|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|DeliveryDate|date|✔️|||
|DeliveryDateTime|object|✔️|||
|DespatchDate|date|✔️|||
|DespatchDateTime|object|✔️|||
|OutstandingToDeliver|number||||
|OutstandingToPickRequest|number|✔️|||

## Relationships
### Many to One

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|CustomerEntity|[Customer](Customer.md)|Customer_OrderSelection|✔️||
|MaterialEntity|[Material](Material.md)|Customer_OrderSelection|✔️||
|Product_OptionEntity|[Product_Option](Product_Option.md)|Customer_OrderSelection|✔️||
|ProductEntity|[Product](Product.md)|Customer_OrderSelection|✔️||

### One to Many

|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|CofCSelection|[CofC](CofC.md)|Customer_OrderEntity|✔️||
|OrderPickRequestSelection|[OrderPickRequest](OrderPickRequest.md)|Customer_OrderEntity|✔️||

## Class Functions

### [DataClass Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer_Order.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|classicMakeOrderSort()|✔️||
|classicOrderOverviewSort()|✔️||

### [Entity Functions](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer_OrderEntity.4dm)

|Name|Local|Notes|
|:---|:---:|:---:|
|createCofC()|✔️||
|getAvailableForPickRequest()|✔️||
|modifyOrderPickRequest()|✔️||
|getPickRequestedQuantity()|✔️||
|getPickedQuantity()|✔️||
|getPickedQuantitiesColor()|✔️||
|getPickedQuantitiesText()|✔️||
|getPickRequestQuantitiesText()|✔️||
|getPickRequestQuantitiesColor()|✔️||