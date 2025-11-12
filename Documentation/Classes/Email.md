# Email

## Description

if(Match regex(Email Regex;$EmailAddress))

## Table of Contents

### Properties

- [EmailObject](#emailobject)
- [_PermissionFooterCollection](#permissionfootercollection)

### Functions

- [constructor() [constructor]](#constructor)
- [addTo()](#addto)
- [addCc()](#addcc)
- [addBcc()](#addbcc)
- [addPermissionGroup()](#addpermissiongroup)
- [addCustomerGroup()](#addcustomergroup)
- [setFromAddress()](#setfromaddress)
- [setFromCurrentUser()](#setfromcurrentuser)
- [setMessageID()](#setmessageid)
- [setHtmlBody()](#sethtmlbody)
- [setSubject()](#setsubject)
- [attachFile()](#attachfile)
- [send()](#send)

---

## Properties

### EmailObject {#emailobject}

**Type:** `Object`

---

### _PermissionFooterCollection {#permissionfootercollection}

**Type:** `Collection`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($Subject : Text; $HTML_Body : Text)
```

---

### addTo {#addto}


```4d
Function addTo($EmailAddress : Text)
```

---

### addCc {#addcc}


```4d
Function addCc($EmailAddress : Text)
```

---

### addBcc {#addbcc}


```4d
Function addBcc($EmailAddress : Text)
```

---

### addPermissionGroup {#addpermissiongroup}


```4d
Function addPermissionGroup($PermissionName : Text; $RecipientType : Integer; $ShowPermissionFooter : Boolean)
```

---

### addCustomerGroup {#addcustomergroup}


```4d
Function addCustomerGroup($CustomerCode : Text)
```

---

### setFromAddress {#setfromaddress}


```4d
Function setFromAddress($EmailAddress : Text; $EmailName : Text)
```

---

### setFromCurrentUser {#setfromcurrentuser}


```4d
Function setFromCurrentUser -> Boolean
```

**Returns:** `Boolean`

---

### setMessageID {#setmessageid}


```4d
Function setMessageID($MessageID : Text)
```

---

### setHtmlBody {#sethtmlbody}


```4d
Function setHtmlBody($HTML_Body : Text)
```

---

### setSubject {#setsubject}


```4d
Function setSubject($Subject : Text)
```

---

### attachFile {#attachfile}


```4d
Function attachFile($FilePathBlobOrObject : Variant; $BlobFileName : Text)
```

---

### send {#send}


```4d
Function send -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from Email.4dm*
*Last updated: 2025-11-12T17:17:31.562Z*
