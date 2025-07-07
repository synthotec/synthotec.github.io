# Stock_Movement Table
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
|Advice_Note_No_i|number|||||✔️|||
|Cert_Of_Conformance_No_i|number|||||✔️|||
|Date_Of_Movement_d|date||||✔️|✔️|||
|DeliveryMethod_txt|string|||||✔️|||
|From_Location_l|number|||||✔️|||
|FullPallet_l|number|||||✔️|||
|is_consigment_stock_b|bool|||||✔️|||
|MoveListNum|number|||||✔️|||
|Movement_Type_From_s|string|||||✔️|||
|Movement_Type_To_s|string|||||✔️|||
|NSKFromBox|number|||||✔️|||
|NSKToBox|number|||||✔️|||
|Order_No_s|string|||||✔️|||
|ProductID_l|number||||✔️|✔️|||
|Quantity_In_l|number|||||✔️|||
|Quantity_Out_l|number|||||✔️|||
|Reason_For_Movement_txt|string|||||✔️|||
|Stock_Movement_b|bool|||||✔️|||
|StockMovementID_l|number|||||✔️|||
|To_Location_l|number|||||✔️|||
|TransactionID|number|||||✔️|||
|UserName_txt|string|||||✔️|||
|Works_Order_No_l|number||||✔️|✔️|||
## Relationships
### Many to One
|Name|Related Table|Inverse Name|Exposed|Notes|
|:---|:---:|:---:|:---:|:---:|
|Stock_LocationEntity|[Stock_Location](Stock_Location.md)|Stock_MovementSelection|✔️||
|WorksOrderEntity|[WorksOrder](WorksOrder.md)|Stock_MovementSelection|✔️||