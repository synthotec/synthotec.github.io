---
layout : default
title : RestPostData
parent : Classes
---
# RestPostData [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RestPostData.4dm)

📊 **Overview:** 4 Properties | 1 Constructor | 5 Functions

## 📝 Description

Creates REST post data handler from object containing JSON strings and staff ID

🕐 *Last updated: 2026-01-13T16:04:13.298Z*

---

## 📑 Table of Contents

- [📋 Properties (4)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getStaffEntity](#getstaffentity) → `cs.StaffEntity`
    - [getScannerObject](#getscannerobject) → `Object`
    - [getScannerText](#getscannertext) → `Text`
    - [getRestPostObject](#getrestpostobject) → `Object`
    - [toObject](#toobject) → `Object`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `RestPostJson` | `Text` | - | JSON string from REST POST request |
| `ScannerData` | `Text` | - | Raw scanner input data |
| `PromptResult` | `Text` | - | Result from user prompt dialog |
| `StaffID` | `Integer` | - | ID of staff member associated with request |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($RestPostDataObject : Object)
```

Creates REST post data handler from object containing JSON strings and staff ID

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### getStaffEntity {#getstaffentity}


```4d
Function getStaffEntity -> cs.StaffEntity
```

Returns the staff entity associated with this request

**Returns:** `cs.StaffEntity`

---

#### getScannerObject {#getscannerobject}


```4d
Function getScannerObject -> Object
```

Parses and returns scanner data as object, returns Null on parse error

**Returns:** `Object`

---

#### getScannerText {#getscannertext}


```4d
Function getScannerText -> Text
```

Returns the raw scanner data text

**Returns:** `Text`

---

#### getRestPostObject {#getrestpostobject}


```4d
Function getRestPostObject -> Object
```

Parses and returns REST POST JSON as object, returns Null on parse error

**Returns:** `Object`

---

#### toObject {#toobject}


```4d
Function toObject -> Object
```

Converts this object to a plain object suitable for serialization

**Returns:** `Object`

---

---

*Generated from RestPostData.4dm*
