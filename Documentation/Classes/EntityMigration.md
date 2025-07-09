---
layout: default
title: EntityMigration ⌛
parent: Classes
---

# EntityMigration

|   |
|:---|
|[**.new**( *DataClass* : 4D.DataClass; *LinkRemoteSelection* : 4D.EntitySelection )](#new)<br>|
|[**.get LinkAdditionalInfoProperty**() : Text](#get linkadditionalinfoproperty)<br>|
|[**.sync**( *Entity* : 4D.Entity; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity](#sync)<br>|
|[**.get LinkDisplayProperty**() : Text](#get linkdisplayproperty)<br>|
|[**.get LinkingEnabled**() : Boolean](#get linkingenabled)<br>|
|[**.LinkDisplayPropertyValue**( *Entity* : 4D.Entity ) : Variant](#linkdisplaypropertyvalue)<br>|
|[**.link**( *Entity* : 4D.Entity; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity](#link)<br>|
|[**.create**( *Entity* : 4D.Entity; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity](#create)<br>|
|[**.get**( *Entity* : 4D.Entity; *LinkEntity* : Boolean; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity](#get)<br>|
|[**.get NewEntityPropertyFormulas**() : Collection](#get newentitypropertyformulas)<br>|
|[**.get _MigrationSettings**() : Object](#get _migrationsettings)<br>|
|[**.get DataClassName**() : Text](#get dataclassname)<br>|
|[**.get MigrationPropertyExists**() : Boolean](#get migrationpropertyexists)<br>|
|[**.updateLoading**( *LoadingText* : Text; *Entity* : 4D.Entity )](#updateloading)<br>|
|[**.startTransactions**()](#starttransactions)<br>|
|[**.validateTransactions**()](#validatetransactions)<br>|
|[**.cancelTransactions**()](#canceltransactions)<br>|
|[LinkRemoteSelection : 4D.EntitySelection](#linkremoteselection)<br>|
|[LinkFunctionCancelled : Boolean](#linkfunctioncancelled)<br>|
|[RemoteDataClass : 4D.DataClass](#remotedataclass)<br>|
|[Loading : cs.Loading](#loading)<br>|


## new()
**.new**( *DataClass* : 4D.DataClass; *LinkRemoteSelection* : 4D.EntitySelection )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|DataClass|4D.DataClass|->|<Description>|
|LinkRemoteSelection|4D.EntitySelection|->|<Description>|

## get LinkAdditionalInfoProperty()
**.get LinkAdditionalInfoProperty**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## sync()
**.sync**( *Entity* : 4D.Entity; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Entity|4D.Entity|->|<Description>|
|PreventSync|Boolean|->|<Description>|
|RemoteEntity|4D.Entity|<-|<Description>|

## get LinkDisplayProperty()
**.get LinkDisplayProperty**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get LinkingEnabled()
**.get LinkingEnabled**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## LinkDisplayPropertyValue()
**.LinkDisplayPropertyValue**( *Entity* : 4D.Entity ) : Variant

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Entity|4D.Entity|->|<Description>|
||Variant|<-|<Description>|

## link()
**.link**( *Entity* : 4D.Entity; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Entity|4D.Entity|->|<Description>|
|PreventSync|Boolean|->|<Description>|
|RemoteEntity|4D.Entity|<-|<Description>|

## create()
**.create**( *Entity* : 4D.Entity; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Entity|4D.Entity|->|<Description>|
|PreventSync|Boolean|->|<Description>|
|RemoteEntity|4D.Entity|<-|<Description>|

## get()
**.get**( *Entity* : 4D.Entity; *LinkEntity* : Boolean; *PreventSync* : Boolean )->RemoteEntity : 4D.Entity

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Entity|4D.Entity|->|<Description>|
|LinkEntity|Boolean|->|<Description>|
|PreventSync|Boolean|->|<Description>|
|RemoteEntity|4D.Entity|<-|<Description>|

## get NewEntityPropertyFormulas()
**.get NewEntityPropertyFormulas**() : Collection

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Collection|<-|<Description>|

## get _MigrationSettings()
**.get _MigrationSettings**() : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Object|<-|<Description>|

## get DataClassName()
**.get DataClassName**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get MigrationPropertyExists()
**.get MigrationPropertyExists**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## updateLoading()
**.updateLoading**( *LoadingText* : Text; *Entity* : 4D.Entity )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|LoadingText|Text|->|<Description>|
|Entity|4D.Entity|->|<Description>|

## startTransactions()
**.startTransactions**()


## validateTransactions()
**.validateTransactions**()


## cancelTransactions()
**.cancelTransactions**()


## LinkRemoteSelection
LinkRemoteSelection : 4D.EntitySelection


## LinkFunctionCancelled
LinkFunctionCancelled : Boolean


## RemoteDataClass
RemoteDataClass : 4D.DataClass


## Loading
Loading : cs.Loading

