---
layout : default
title : FormInspector
parent : Classes
---
# FormInspector [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/FormInspector.4dm)

📊 **Overview:** 1 Constructor | 7 Functions

## 📝 Description

🗨️ Parse 4D form.4DForm file and extract form metadata for documentation

🕐 *Last updated: 2025-11-14T00:02:22.284Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#-constructor) (1 param)
- [⚙️ Functions](#️-functions)
  - [_parseForm](#_parseform)
  - [_countObjects](#_countobjects) (1 param)
  - [_getTableName](#_gettablename) (1 param) → `Text`
  - [_mergeExistingData](#_mergeexistingdata)
  - [toObject](#toobject) → `Object`
  - [toJSON](#tojson) → `Text`
  - [saveToFile](#savetofile)
---

## 🏗️ Constructor

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($FormName : Text)
```

Parse 4D form.4DForm file and extract form metadata for documentation

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FormName` | `Text` | - | - |

---

## ⚙️ Functions

### Regular Functions

#### _parseForm {#_parseform}


```4d
Function _parseForm
```

Parse the form.4DForm JSON file

---

#### _countObjects {#_countobjects}


```4d
Function _countObjects($Pages : Collection)
```

Count objects by type across all pages and collect interactive object details

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Pages` | `Collection` | - | - |

---

#### _getTableName {#_gettablename}


```4d
Function _getTableName($TableNumber : Integer) -> Text
```

Get table name from table number

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TableNumber` | `Integer` | - | - |

**Returns:** `Text`

---

#### _mergeExistingData {#_mergeexistingdata}


```4d
Function _mergeExistingData
```

Preserve manual comment

---

#### toObject {#toobject}


```4d
Function toObject -> Object
```

Convert to object for JSON export

**Returns:** `Object`

---

#### toJSON {#tojson}


```4d
Function toJSON -> Text
```

Convert to JSON string

**Returns:** `Text`

---

#### saveToFile {#savetofile}


```4d
Function saveToFile
```

Save to file

---

---

*Generated from FormInspector.4dm*
