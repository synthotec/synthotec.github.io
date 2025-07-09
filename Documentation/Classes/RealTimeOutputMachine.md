---
layout: default
title: RealTimeOutputMachine ⌛
parent: Classes
---

# RealTimeOutputMachine

|   |
|:---|
|[**.new**( *RealTimeMachinesEntity* : cs.RealTimeMachinesEntity )](#new)<br>|
|[**.ProcessColors**()](#processcolors)<br>|
|[**.setDateTimeColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )](#setdatetimecolors)<br>|
|[**.get SecondaryStatusText**()->DateTimeObject : Object](#get secondarystatustext)<br>|
|[**.get TimeRemainingText**()->DateTimeObject : Object](#get timeremainingtext)<br>|
|[**.get MouldStatusText**() : Text](#get mouldstatustext)<br>|
|[**.setPrimaryColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )](#setprimarycolors)<br>|
|[**.get DeviceMaintenanceActive**() : Boolean](#get devicemaintenanceactive)<br>|
|[**.setAlternatingColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )](#setalternatingcolors)<br>|
|[**.setAlertColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )](#setalertcolors)<br>|
|[**.get MachineDisconnected**() : Boolean](#get machinedisconnected)<br>|
|[**.get MachineRunning**() : Boolean](#get machinerunning)<br>|
|[**.get WorksOrderIsOpen**() : Boolean](#get worksorderisopen)<br>|
|[**.get UnacknowledgedSensorExceptions**() : Boolean](#get unacknowledgedsensorexceptions)<br>|
|[**.get PrimaryStatusText**() : Text](#get primarystatustext)<br>|
|[**.get ScrapText**() : Text](#get scraptext)<br>|
|[**.get PartsMadeText**() : Text](#get partsmadetext)<br>|
|[**.get AlertsText**() : Text](#get alertstext)<br>|
|[**.get PercentMade**() : Real](#get percentmade)<br>|
|[**.get MachineNumberText**() : Text](#get machinenumbertext)<br>|
|[**.get PartNameText**() : Text](#get partnametext)<br>|
|[**.get UnicodeSymbolsText**() : Text](#get unicodesymbolstext)<br>|
|[**.setTimeRemainingText**( *Text* : Text; *DateTime* : Variant; *AdditionalSeconds* : Real )](#settimeremainingtext)<br>|
|[RealTimeMachinesEntity : cs.RealTimeMachinesEntity](#realtimemachinesentity)<br>|
|[WorksOrderEntity : cs.WorksOrderEntity](#worksorderentity)<br>|
|[ProductEntity : cs.ProductEntity](#productentity)<br>|
|[RunningSlow : Boolean](#runningslow)<br>|
|[ToolsEntity : cs.ToolsEntity](#toolsentity)<br>|
|[AverageCycleTime : Real](#averagecycletime)<br>|
|[DownReasonsEntity : cs.DownReasonsEntity](#downreasonsentity)<br>|


## new()
**.new**( *RealTimeMachinesEntity* : cs.RealTimeMachinesEntity )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|RealTimeMachinesEntity|cs.RealTimeMachinesEntity|->|<Description>|

## ProcessColors()
**.ProcessColors**()


## setDateTimeColors()
**.setDateTimeColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|BackgroundColor|Integer|->|<Description>|
|ForegroundColor|Integer|->|<Description>|

## get SecondaryStatusText()
**.get SecondaryStatusText**()->DateTimeObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|DateTimeObject|Object|<-|<Description>|

## get TimeRemainingText()
**.get TimeRemainingText**()->DateTimeObject : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|DateTimeObject|Object|<-|<Description>|

## get MouldStatusText()
**.get MouldStatusText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## setPrimaryColors()
**.setPrimaryColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|BackgroundColor|Integer|->|<Description>|
|ForegroundColor|Integer|->|<Description>|

## get DeviceMaintenanceActive()
**.get DeviceMaintenanceActive**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## setAlternatingColors()
**.setAlternatingColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|BackgroundColor|Integer|->|<Description>|
|ForegroundColor|Integer|->|<Description>|

## setAlertColors()
**.setAlertColors**( *BackgroundColor* : Integer; *ForegroundColor* : Integer )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|BackgroundColor|Integer|->|<Description>|
|ForegroundColor|Integer|->|<Description>|

## get MachineDisconnected()
**.get MachineDisconnected**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get MachineRunning()
**.get MachineRunning**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get WorksOrderIsOpen()
**.get WorksOrderIsOpen**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get UnacknowledgedSensorExceptions()
**.get UnacknowledgedSensorExceptions**() : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Boolean|<-|<Description>|

## get PrimaryStatusText()
**.get PrimaryStatusText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get ScrapText()
**.get ScrapText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get PartsMadeText()
**.get PartsMadeText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get AlertsText()
**.get AlertsText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get PercentMade()
**.get PercentMade**() : Real

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Real|<-|<Description>|

## get MachineNumberText()
**.get MachineNumberText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get PartNameText()
**.get PartNameText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## get UnicodeSymbolsText()
**.get UnicodeSymbolsText**() : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
||Text|<-|<Description>|

## setTimeRemainingText()
**.setTimeRemainingText**( *Text* : Text; *DateTime* : Variant; *AdditionalSeconds* : Real )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Text|Text|->|<Description>|
|DateTime|Variant|->|<Description>|
|AdditionalSeconds|Real|->|<Description>|

## RealTimeMachinesEntity
RealTimeMachinesEntity : cs.RealTimeMachinesEntity


## WorksOrderEntity
WorksOrderEntity : cs.WorksOrderEntity


## ProductEntity
ProductEntity : cs.ProductEntity


## RunningSlow
RunningSlow : Boolean


## ToolsEntity
ToolsEntity : cs.ToolsEntity


## AverageCycleTime
AverageCycleTime : Real


## DownReasonsEntity
DownReasonsEntity : cs.DownReasonsEntity

