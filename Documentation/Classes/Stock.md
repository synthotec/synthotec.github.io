---
layout: default
title: Stock ⌛
parent: Classes
---

# Stock

|   |
|:---|
|[**.new**( *DataStore* : 4D.DataStoreImplementation; *WorksOrder* : Integer )](#new)<br>|
|[**.adjust**( *LocationID* : Integer; *AdjustmentQuantity* : Integer; *CreateStockMovement* : Boolean; *AdjustmentReason* : Text; *AdviceNote* : Integer )->lockObject : Object](#adjust)<br>|
|[**.Quarantine_Stock**( *QuantityToQuarantine* : Integer; *QuarantineReason* : Text )->lockObject : Object](#quarantine_stock)<br>|
|[**.move**( *FromLocation* : Integer; *ToLocation* : Integer; *AdjustmentQuantity* : Integer; *AdjustmentReason* : Text; *AdviceNote* : Integer )->lockObject : Object](#move)<br>|
|[**.Quarantine_Release**( *QuantityToRelease* : Integer; *ReleaseReason* : Text )->lockObject : Object](#quarantine_release)<br>|
|[**.GetQuarantinedQuantity**()->QuarantinedQuantity : Integer](#getquarantinedquantity)<br>|
|[**.SetNewStockQuarantineStatus**( *QuarantineNewStock* : Boolean )->lockObject : Object](#setnewstockquarantinestatus)<br>|
|[**.GetAvailableQuantity**( *StockLocation* : Integer )->AvailableQuantity : Integer](#getavailablequantity)<br>|
|[**.Quarantine_Scrap**( *QuantityToScrap* : Integer; *ScrapReason* : Text )->lockObject : Object](#quarantine_scrap)<br>|
|[**.validateTransaction**()](#validatetransaction)<br>|
|[**.startTransaction**()](#starttransaction)<br>|
|[**.cancelTransaction**()](#canceltransaction)<br>|
|[**.InTransaction**()->InTransaction : Boolean](#intransaction)<br>|
|[**.SetQuarantineReason**( *QuarantineReason* : Text )->lockObject : Object](#setquarantinereason)<br>|
|[**.GetStockEntitySelection**()->EntitySelection : 4D.EntitySelection](#getstockentityselection)<br>|
|[**.GetNewStockQuarantineStatus**()->QuarantineNewStock : Boolean](#getnewstockquarantinestatus)<br>|
|[**.GetQuarantineReason**()->QuarantineReason : Text](#getquarantinereason)<br>|


## new()
**.new**( *DataStore* : 4D.DataStoreImplementation; *WorksOrder* : Integer )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|DataStore|4D.DataStoreImplementation|->|<Description>|
|WorksOrder|Integer|->|<Description>|

## adjust()
**.adjust**( *LocationID* : Integer; *AdjustmentQuantity* : Integer; *CreateStockMovement* : Boolean; *AdjustmentReason* : Text; *AdviceNote* : Integer )->lockObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|LocationID|Integer|->|<Description>|
|AdjustmentQuantity|Integer|->|<Description>|
|CreateStockMovement|Boolean|->|<Description>|
|AdjustmentReason|Text|->|<Description>|
|AdviceNote|Integer|->|<Description>|
|lockObject|Object|<-|<Description>|

## Quarantine_Stock()
**.Quarantine_Stock**( *QuantityToQuarantine* : Integer; *QuarantineReason* : Text )->lockObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuantityToQuarantine|Integer|->|<Description>|
|QuarantineReason|Text|->|<Description>|
|lockObject|Object|<-|<Description>|

## move()
**.move**( *FromLocation* : Integer; *ToLocation* : Integer; *AdjustmentQuantity* : Integer; *AdjustmentReason* : Text; *AdviceNote* : Integer )->lockObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|FromLocation|Integer|->|<Description>|
|ToLocation|Integer|->|<Description>|
|AdjustmentQuantity|Integer|->|<Description>|
|AdjustmentReason|Text|->|<Description>|
|AdviceNote|Integer|->|<Description>|
|lockObject|Object|<-|<Description>|

## Quarantine_Release()
**.Quarantine_Release**( *QuantityToRelease* : Integer; *ReleaseReason* : Text )->lockObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuantityToRelease|Integer|->|<Description>|
|ReleaseReason|Text|->|<Description>|
|lockObject|Object|<-|<Description>|

## GetQuarantinedQuantity()
**.GetQuarantinedQuantity**()->QuarantinedQuantity : Integer

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuarantinedQuantity|Integer|<-|<Description>|

## SetNewStockQuarantineStatus()
**.SetNewStockQuarantineStatus**( *QuarantineNewStock* : Boolean )->lockObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuarantineNewStock|Boolean|->|<Description>|
|lockObject|Object|<-|<Description>|

## GetAvailableQuantity()
**.GetAvailableQuantity**( *StockLocation* : Integer )->AvailableQuantity : Integer

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|StockLocation|Integer|->|<Description>|
|AvailableQuantity|Integer|<-|<Description>|

## Quarantine_Scrap()
**.Quarantine_Scrap**( *QuantityToScrap* : Integer; *ScrapReason* : Text )->lockObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuantityToScrap|Integer|->|<Description>|
|ScrapReason|Text|->|<Description>|
|lockObject|Object|<-|<Description>|

## validateTransaction()
**.validateTransaction**()


## startTransaction()
**.startTransaction**()


## cancelTransaction()
**.cancelTransaction**()


## InTransaction()
**.InTransaction**()->InTransaction : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|InTransaction|Boolean|<-|<Description>|

## SetQuarantineReason()
**.SetQuarantineReason**( *QuarantineReason* : Text )->lockObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuarantineReason|Text|->|<Description>|
|lockObject|Object|<-|<Description>|

## GetStockEntitySelection()
**.GetStockEntitySelection**()->EntitySelection : 4D.EntitySelection

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|EntitySelection|4D.EntitySelection|<-|<Description>|

## GetNewStockQuarantineStatus()
**.GetNewStockQuarantineStatus**()->QuarantineNewStock : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuarantineNewStock|Boolean|<-|<Description>|

## GetQuarantineReason()
**.GetQuarantineReason**()->QuarantineReason : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|QuarantineReason|Text|<-|<Description>|
