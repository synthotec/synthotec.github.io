---
layout: default
title: GitHubApi ⌛
parent: Classes
---

# GitHubApi

|   |
|:---|
|[**.new**()](#new)<br>|
|[**.newHttpRequest**( *Url* : Text; *Method* : Text; *Body* : Variant ) : 4D.HTTPRequest](#newhttprequest)<br>|
|[**.createIssue**( *Title* : Text; *Body* : Text; *Labels* : Collection ) : Object](#createissue)<br>|
|[**.getIssues**( *Label* : Text ) : Collection](#getissues)<br>|
|[**.onError**( *HttpRequest* : 4D.HTTPRequest; *Event* : Object )](#onerror)<br>|


## new()
**.new**()


## newHttpRequest()
**.newHttpRequest**( *Url* : Text; *Method* : Text; *Body* : Variant ) : 4D.HTTPRequest

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Url|Text|->|<Description>|
|Method|Text|->|<Description>|
|Body|Variant|->|<Description>|
||4D.HTTPRequest|<-|<Description>|

## createIssue()
**.createIssue**( *Title* : Text; *Body* : Text; *Labels* : Collection ) : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Title|Text|->|<Description>|
|Body|Text|->|<Description>|
|Labels|Collection|->|<Description>|
||Object|<-|<Description>|

## getIssues()
**.getIssues**( *Label* : Text ) : Collection

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Label|Text|->|<Description>|
||Collection|<-|<Description>|

## onError()
**.onError**( *HttpRequest* : 4D.HTTPRequest; *Event* : Object )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|HttpRequest|4D.HTTPRequest|->|<Description>|
|Event|Object|->|<Description>|
