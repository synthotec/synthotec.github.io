---
layout : default
title : Email
parent : Classes
---
# Email

📊 **Overview:** 2 Properties | 1 Constructor | 12 Functions

## 📝 Description

🗨️ if(Match regex(Email Regex;$EmailAddress))

🕐 *Last updated: 2025-11-13T01:17:23.001Z*

---

## 📑 Table of Contents

### 📋 Properties (2)

- [EmailObject](#emailobject) : `Object`
- [_PermissionFooterCollection](#permissionfootercollection) : `Collection`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Functions (12):**

- [addTo](#addto) (1 param)
- [addCc](#addcc) (1 param)
- [addBcc](#addbcc) (1 param)
- [addPermissionGroup](#addpermissiongroup) (3 params)
- [addCustomerGroup](#addcustomergroup) (1 param)
- [setFromAddress](#setfromaddress) (2 params)
- [setFromCurrentUser](#setfromcurrentuser) → `Boolean`
- [setMessageID](#setmessageid) (1 param)
- [setHtmlBody](#sethtmlbody) (1 param)
- [setSubject](#setsubject) (1 param)
- [attachFile](#attachfile) (2 params)
- [send](#send) → `Boolean`

---

## 📋 Properties

### Quick Reference

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `EmailObject` | `Object` | - |  |
| `_PermissionFooterCollection` | `Collection` | - |  |

### Detailed Information

#### EmailObject {#emailobject}

**Type:** `Object`

---

#### _PermissionFooterCollection {#permissionfootercollection}

**Type:** `Collection`

---

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Subject : Text; $HTML_Body : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Subject` | `Text` | - | - |
| `$HTML_Body` | `Text` | - | - |

---

### ⚙️ Regular Functions

#### addTo {#addto}


```4d
Function addTo($EmailAddress : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |

---

#### addCc {#addcc}


```4d
Function addCc($EmailAddress : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |

---

#### addBcc {#addbcc}


```4d
Function addBcc($EmailAddress : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |

---

#### addPermissionGroup {#addpermissiongroup}


```4d
Function addPermissionGroup($PermissionName : Text; $RecipientType : Integer; $ShowPermissionFooter : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PermissionName` | `Text` | - | - |
| `$RecipientType` | `Integer` | - | - |
| `$ShowPermissionFooter` | `Boolean` | - | - |

---

#### addCustomerGroup {#addcustomergroup}


```4d
Function addCustomerGroup($CustomerCode : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CustomerCode` | `Text` | - | - |

---

#### setFromAddress {#setfromaddress}


```4d
Function setFromAddress($EmailAddress : Text; $EmailName : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |
| `$EmailName` | `Text` | - | - |

---

#### setFromCurrentUser {#setfromcurrentuser}


```4d
Function setFromCurrentUser -> Boolean
```

**Returns:** `Boolean`

---

#### setMessageID {#setmessageid}


```4d
Function setMessageID($MessageID : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MessageID` | `Text` | - | - |

---

#### setHtmlBody {#sethtmlbody}


```4d
Function setHtmlBody($HTML_Body : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HTML_Body` | `Text` | - | - |

---

#### setSubject {#setsubject}


```4d
Function setSubject($Subject : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Subject` | `Text` | - | - |

---

#### attachFile {#attachfile}


```4d
Function attachFile($FilePathBlobOrObject : Variant; $BlobFileName : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FilePathBlobOrObject` | `Variant` | - | - |
| `$BlobFileName` | `Text` | - | - |

---

#### send {#send}


```4d
Function send -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from Email.4dm*
