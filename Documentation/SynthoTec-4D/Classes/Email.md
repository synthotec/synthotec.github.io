---
layout : default
title : Email
parent : Classes
---
# Email [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Email.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 12 Functions

## 📝 Description

Creates a new email with the specified subject and HTML body

🕐 *Last updated: 2025-11-20T14:23:48.831Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [addTo](#addto) (1 param)
    - [addCc](#addcc) (1 param)
    - [addBcc](#addbcc) (1 param)
    - [addPermissionGroup](#addpermissiongroup) (3 params)
    - [addCustomerGroup](#addcustomergroup) (1 param)
    - [setFromAddress](#setfromaddress) (2 params)
    - [setFromCurrentUser](#setfromcurrentuser) → `$Success : Boolean`
    - [setMessageID](#setmessageid) (1 param)
    - [setHtmlBody](#sethtmlbody) (1 param)
    - [setSubject](#setsubject) (1 param)
    - [attachFile](#attachfile) (2 params)
    - [send](#send) → `$EmailSent : Boolean`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `EmailObject` | `Object` | `{}` | The main email object containing all email properties (to, from, subject, body, attachments, etc.) |
| `_PermissionFooterCollection` | `Collection` | `[]` | Internal collection tracking permission groups for footer display |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Subject : Text; $HTML_Body : Text)
```

Creates a new email with the specified subject and HTML body

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Subject` | `Text` | - | - |
| `$HTML_Body` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### addTo {#addto}


```4d
Function addTo($EmailAddress : Text)
```

Adds an email address to the To recipients list (only if not already present)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |

---

#### addCc {#addcc}


```4d
Function addCc($EmailAddress : Text)
```

Adds an email address to the CC (carbon copy) recipients list (only if not already present)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |

---

#### addBcc {#addbcc}


```4d
Function addBcc($EmailAddress : Text)
```

Adds an email address to the BCC (blind carbon copy) recipients list (only if not already present)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |

---

#### addPermissionGroup {#addpermissiongroup}


```4d
Function addPermissionGroup($PermissionName : Text; $RecipientType : Integer; $ShowPermissionFooter : Boolean)
```

Adds all staff members with the specified permission to recipients, optionally showing permission name in footer

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

Adds all contacts for the specified customer code to the To recipients list

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CustomerCode` | `Text` | - | - |

---

#### setFromAddress {#setfromaddress}


```4d
Function setFromAddress($EmailAddress : Text; $EmailName : Text)
```

Sets the sender's email address and optional display name (appends @TLD if no @ present)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EmailAddress` | `Text` | - | - |
| `$EmailName` | `Text` | - | - |

---

#### setFromCurrentUser {#setfromcurrentuser}


```4d
Function setFromCurrentUser -> $Success : Boolean
```

Sets the sender to the currently logged-in user's email and name from Storage.User.ID

**Returns:** `Boolean`

---

#### setMessageID {#setmessageid}


```4d
Function setMessageID($MessageID : Text)
```

Sets the email's message ID and reply-to ID (appends @TLD to the provided ID)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MessageID` | `Text` | - | - |

---

#### setHtmlBody {#sethtmlbody}


```4d
Function setHtmlBody($HTML_Body : Text)
```

Sets the HTML body content of the email

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HTML_Body` | `Text` | - | - |

---

#### setSubject {#setsubject}


```4d
Function setSubject($Subject : Text)
```

Sets the subject line of the email

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Subject` | `Text` | - | - |

---

#### attachFile {#attachfile}


```4d
Function attachFile($FilePathBlobOrObject : Variant; $BlobFileName : Text)
```

Attaches a file to the email - accepts file path (Text), BLOB, 4D.Blob, or 4D.File object

🗨️ **Note:** Additional warning about file size limits, file path format, etc.

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FilePathBlobOrObject` | `Variant` | - | - |
| `$BlobFileName` | `Text` | - | - |

---

#### send {#send}


```4d
Function send -> $EmailSent : Boolean
```

Sends the email using SMTP settings from database, adds permission footer if applicable, returns success status

**Returns:** `Boolean`

---

---

*Generated from Email.4dm*
