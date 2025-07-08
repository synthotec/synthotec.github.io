---
layout: default
title: Email
parent: Classes
---

# Email

|   |
|:---|
|[**.new**( *Subject* : Text; *HTML_Body* : Text )](#new())<br>|
|[**.addTo**( *EmailAddress* : Text )](#addTo())<br>|
|[**.setFromAddress**( *EmailAddress* : Text; *EmailName* : Text )](#setFromAddress())<br>|
|[**.addCc**( *EmailAddress* : Text )](#addCc())<br>|
|[**.addBcc**( *EmailAddress* : Text )](#addBcc())<br>|
|[**.addPermissionGroup**( *PermissionName* : Text; *RecipientType* : Integer; *ShowPermissionFooter* : Boolean )](#addPermissionGroup())<br>|
|[**.addCustomerGroup**( *CustomerCode* : Text )](#addCustomerGroup())<br>|
|[**.setFromCurrentUser**()->Success : Boolean](#setFromCurrentUser())<br>|
|[**.setMessageID**( *MessageID* : Text )](#setMessageID())<br>|
|[**.setHtmlBody**( *HTML_Body* : Text )](#setHtmlBody())<br>|
|[**.setSubject**( *Subject* : Text )](#setSubject())<br>|
|[**.attachFile**( *FilePathBlobOrObject* : Variant; *BlobFileName* : Text )](#attachFile())<br>|
|[**.send**()->EmailSent : Boolean](#send())<br>|
|[EmailObject : Object](#EmailObject)<br>|

## new()
**.new**( *Subject* : Text; *HTML_Body* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Subject|Text|->|<Description>|
|HTML_Body|Text|->|<Description>|
## addTo()
**.addTo**( *EmailAddress* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|EmailAddress|Text|->|<Description>|
## setFromAddress()
**.setFromAddress**( *EmailAddress* : Text; *EmailName* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|EmailAddress|Text|->|<Description>|
|EmailName|Text|->|<Description>|
## addCc()
**.addCc**( *EmailAddress* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|EmailAddress|Text|->|<Description>|
## addBcc()
**.addBcc**( *EmailAddress* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|EmailAddress|Text|->|<Description>|
## addPermissionGroup()
**.addPermissionGroup**( *PermissionName* : Text; *RecipientType* : Integer; *ShowPermissionFooter* : Boolean )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|PermissionName|Text|->|<Description>|
|RecipientType|Integer|->|<Description>|
|ShowPermissionFooter|Boolean|->|<Description>|
## addCustomerGroup()
**.addCustomerGroup**( *CustomerCode* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|CustomerCode|Text|->|<Description>|
## setFromCurrentUser()
**.setFromCurrentUser**()->Success : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Success|Boolean|<-|<Description>|
## setMessageID()
**.setMessageID**( *MessageID* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|MessageID|Text|->|<Description>|
## setHtmlBody()
**.setHtmlBody**( *HTML_Body* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|HTML_Body|Text|->|<Description>|
## setSubject()
**.setSubject**( *Subject* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Subject|Text|->|<Description>|
## attachFile()
**.attachFile**( *FilePathBlobOrObject* : Variant; *BlobFileName* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|FilePathBlobOrObject|Variant|->|<Description>|
|BlobFileName|Text|->|<Description>|
## send()
**.send**()->EmailSent : Boolean

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|EmailSent|Boolean|<-|<Description>|
## EmailObject
EmailObject : Object

