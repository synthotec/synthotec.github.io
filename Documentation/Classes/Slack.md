---
layout: default
title: Slack
parent: Classes
---

# Slack

|   |
|:---|
|[**.new**( *ChannelName* : Text )](#new)<br>|
|[**.newHttpRequest**( *Url* : Text; *Options* : Object ) : 4D.HTTPRequest](#newhttprequest)<br>|
|[**.createChannel**( *ChannelName* : Text ) : Text](#createchannel)<br>|
|[**.createMessage**( *HeaderText* : Text; *Blocks* : Collection )->MessageTimeStamp : Text](#createmessage)<br>|
|[**.setChannelID**( *ChannelName* : Text ) : Boolean](#setchannelid)<br>|
|[**.convertBlocks**( *HeaderText* : Text; *Blocks* : Collection )->BlocksCollection : Collection](#convertblocks)<br>|
|[**.deleteMessage**( *MessageTimeStamp* : Text ) : Boolean](#deletemessage)<br>|
|[**.updateMessage**( *MessageTimeStamp* : Text; *text* : Text; *Blocks* : Collection ) : Boolean](#updatemessage)<br>|
|[ChannelID : Text](#channelid)<br>|


## new()
**.new**( *ChannelName* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|ChannelName|Text|->|<Description>|

## newHttpRequest()
**.newHttpRequest**( *Url* : Text; *Options* : Object ) : 4D.HTTPRequest

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Url|Text|->|<Description>|
|Options|Object|->|<Description>|
||4D.HTTPRequest|<-|<Description>|

## createChannel()
**.createChannel**( *ChannelName* : Text ) : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|ChannelName|Text|->|<Description>|
||Text|<-|<Description>|

## createMessage()
**.createMessage**( *HeaderText* : Text; *Blocks* : Collection )->MessageTimeStamp : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|HeaderText|Text|->|<Description>|
|Blocks|Collection|->|<Description>|
|MessageTimeStamp|Text|<-|<Description>|

## setChannelID()
**.setChannelID**( *ChannelName* : Text ) : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|ChannelName|Text|->|<Description>|
||Boolean|<-|<Description>|

## convertBlocks()
**.convertBlocks**( *HeaderText* : Text; *Blocks* : Collection )->BlocksCollection : Collection

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|HeaderText|Text|->|<Description>|
|Blocks|Collection|->|<Description>|
|BlocksCollection|Collection|<-|<Description>|

## deleteMessage()
**.deleteMessage**( *MessageTimeStamp* : Text ) : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|MessageTimeStamp|Text|->|<Description>|
||Boolean|<-|<Description>|

## updateMessage()
**.updateMessage**( *MessageTimeStamp* : Text; *text* : Text; *Blocks* : Collection ) : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|MessageTimeStamp|Text|->|<Description>|
|text|Text|->|<Description>|
|Blocks|Collection|->|<Description>|
||Boolean|<-|<Description>|

## ChannelID
ChannelID : Text

