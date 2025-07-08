---
layout: default
title: PrintSettings
parent: Classes
---

# PrintSettings

|   |
|:---|
|[**.new**( *UseSystemDefaultPrinter* : Boolean; *Paper* : Text; *Copies* : Integer; *Orientation* : Integer )](#new)<br>|
|[**.display**()->Accepted : Boolean](#display)<br>|
|[**.load**( *SettingName* : Text; *LoadCopyCount* : Boolean ) : cs.PrintSettings](#load)<br>|
|[**.restore**()->Success : Boolean](#restore)<br>|
|[**.apply**()->Success : Boolean](#apply)<br>|
|[**.save**( *SettingName* : Text ) : cs.PrintSettings](#save)<br>|
|[CurrentPrinter : Text](#currentprinter)<br>|
|[Paper : Text](#paper)<br>|
|[Name : Text](#name)<br>|
|[Orientation : Integer](#orientation)<br>|
|[Copies : Integer](#copies)<br>|


## new()
**.new**( *UseSystemDefaultPrinter* : Boolean; *Paper* : Text; *Copies* : Integer; *Orientation* : Integer )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|UseSystemDefaultPrinter|Boolean|->|<Description>|
|Paper|Text|->|<Description>|
|Copies|Integer|->|<Description>|
|Orientation|Integer|->|<Description>|

## display()
**.display**()->Accepted : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Accepted|Boolean|<-|<Description>|

## load()
**.load**( *SettingName* : Text; *LoadCopyCount* : Boolean ) : cs.PrintSettings

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|SettingName|Text|->|<Description>|
|LoadCopyCount|Boolean|->|<Description>|
||cs.PrintSettings|<-|<Description>|

## restore()
**.restore**()->Success : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Success|Boolean|<-|<Description>|

## apply()
**.apply**()->Success : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Success|Boolean|<-|<Description>|

## save()
**.save**( *SettingName* : Text ) : cs.PrintSettings

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|SettingName|Text|->|<Description>|
||cs.PrintSettings|<-|<Description>|

## CurrentPrinter
CurrentPrinter : Text


## Paper
Paper : Text


## Name
Name : Text


## Orientation
Orientation : Integer


## Copies
Copies : Integer

