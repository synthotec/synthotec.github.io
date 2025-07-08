---
layout: default
title: ProcurementProgramLine
parent: Classes
---

# ProcurementProgramLine

|   |
|:---|
|[**.new**( *TextLineOrCustomer_OrderEntity* : Variant; *ProcurementProgram* : cs.ProcurementProgram )](#new)<br>|
|[**.get IsExistingOrderModified**() : Boolean](#get isexistingordermodified)<br>|
|[**.newFromCustomerOrder**( *Customer_OrderEntity* : cs.Customer_OrderEntity )](#newfromcustomerorder)<br>|
|[**.get IsActionSet**() : Boolean](#get isactionset)<br>|
|[**.setDefaultActions**()](#setdefaultactions)<br>|
|[**.get IsBacklog**() : Boolean](#get isbacklog)<br>|
|[**.get ActionText**()->ActionText : Text](#get actiontext)<br>|
|[**.get IsItemMissing**() : Boolean](#get isitemmissing)<br>|
|[**.get IsForecast**() : Boolean](#get isforecast)<br>|
|[**.get IsNewOrder**() : Boolean](#get isneworder)<br>|
|[**.get IsExistingOrder**() : Boolean](#get isexistingorder)<br>|
|[**.get WeekNumberText**() : Text](#get weeknumbertext)<br>|
|[**.get OrderBatchNumber**() : Text](#get orderbatchnumber)<br>|
|[**.newFromText**( *Line* : Text )](#newfromtext)<br>|
|[**.getWarehouseWithCustomerCode**() : Text](#getwarehousewithcustomercode)<br>|
|[**.get OurPartName**() : Text](#get ourpartname)<br>|
|[**.get Meta**()->Meta : cs.UI.ListBoxMeta](#get meta)<br>|
|[**.get StatusText**()->StatusText : Text](#get statustext)<br>|
|[**.process_CloseOrder**()](#process_closeorder)<br>|
|[**.setAction**()](#setaction)<br>|
|[**.process**()](#process)<br>|
|[**.process_CreateForecast**()](#process_createforecast)<br>|
|[**.process_UpdateOrder**()](#process_updateorder)<br>|
|[**.process_CreateOrder**()](#process_createorder)<br>|
|[ItemDescription : Text](#itemdescription)<br>|
|[ItemNumber : Text](#itemnumber)<br>|
|[OrderNumber : Text](#ordernumber)<br>|
|[Quantity : Integer](#quantity)<br>|
|[Vmi : Boolean](#vmi)<br>|
|[DueDate : Date](#duedate)<br>|
|[Warehouse : Text](#warehouse)<br>|
|[Action_Ignore : Boolean](#action_ignore)<br>|
|[Product_OptionEntity : cs.Product_OptionEntity](#product_optionentity)<br>|
|[Customer_OrderEntity : cs.Customer_OrderEntity](#customer_orderentity)<br>|
|[ProcurementProgram : cs.ProcurementProgram](#procurementprogram)<br>|
|[RemovedFromProgram : Boolean](#removedfromprogram)<br>|
|[Action_CreateForecast : Boolean](#action_createforecast)<br>|
|[Action_CreateOrder : Boolean](#action_createorder)<br>|
|[Action_CloseOrder : Boolean](#action_closeorder)<br>|
|[Action_UpdateOrder : Boolean](#action_updateorder)<br>|
|[WarehouseWithCustomerCode : Text](#warehousewithcustomercode)<br>|
|[ds : 4D.DataStoreImplementation](#ds)<br>|


## new()
**.new**( *TextLineOrCustomer_OrderEntity* : Variant; *ProcurementProgram* : cs.ProcurementProgram )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|TextLineOrCustomer_OrderEntity|Variant|->|<Description>|
|ProcurementProgram|cs.ProcurementProgram|->|<Description>|

## get IsExistingOrderModified()
**.get IsExistingOrderModified**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## newFromCustomerOrder()
**.newFromCustomerOrder**( *Customer_OrderEntity* : cs.Customer_OrderEntity )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Customer_OrderEntity|cs.Customer_OrderEntity|->|<Description>|

## get IsActionSet()
**.get IsActionSet**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## setDefaultActions()
**.setDefaultActions**()


## get IsBacklog()
**.get IsBacklog**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get ActionText()
**.get ActionText**()->ActionText : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|ActionText|Text|<-|<Description>|

## get IsItemMissing()
**.get IsItemMissing**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get IsForecast()
**.get IsForecast**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get IsNewOrder()
**.get IsNewOrder**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get IsExistingOrder()
**.get IsExistingOrder**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get WeekNumberText()
**.get WeekNumberText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get OrderBatchNumber()
**.get OrderBatchNumber**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## newFromText()
**.newFromText**( *Line* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Line|Text|->|<Description>|

## getWarehouseWithCustomerCode()
**.getWarehouseWithCustomerCode**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get OurPartName()
**.get OurPartName**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get Meta()
**.get Meta**()->Meta : cs.UI.ListBoxMeta

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Meta|cs.UI.ListBoxMeta|<-|<Description>|

## get StatusText()
**.get StatusText**()->StatusText : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|StatusText|Text|<-|<Description>|

## process_CloseOrder()
**.process_CloseOrder**()


## setAction()
**.setAction**()


## process()
**.process**()


## process_CreateForecast()
**.process_CreateForecast**()


## process_UpdateOrder()
**.process_UpdateOrder**()


## process_CreateOrder()
**.process_CreateOrder**()


## ItemDescription
ItemDescription : Text


## ItemNumber
ItemNumber : Text


## OrderNumber
OrderNumber : Text


## Quantity
Quantity : Integer


## Vmi
Vmi : Boolean


## DueDate
DueDate : Date


## Warehouse
Warehouse : Text


## Action_Ignore
Action_Ignore : Boolean


## Product_OptionEntity
Product_OptionEntity : cs.Product_OptionEntity


## Customer_OrderEntity
Customer_OrderEntity : cs.Customer_OrderEntity


## ProcurementProgram
ProcurementProgram : cs.ProcurementProgram


## RemovedFromProgram
RemovedFromProgram : Boolean


## Action_CreateForecast
Action_CreateForecast : Boolean


## Action_CreateOrder
Action_CreateOrder : Boolean


## Action_CloseOrder
Action_CloseOrder : Boolean


## Action_UpdateOrder
Action_UpdateOrder : Boolean


## WarehouseWithCustomerCode
WarehouseWithCustomerCode : Text


## ds
ds : 4D.DataStoreImplementation

