---
layout : default
title : GitHubApi
parent : Classes
---
# GitHubApi [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/GitHubApi.4dm)

📊 **Overview:** 1 Constructor | 4 Functions

🕐 *Last updated: 2025-11-14T00:02:22.334Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#-constructor)
- [⚙️ Functions](#️-functions)
  - [newHttpRequest](#newhttprequest) (3 params) → `4D.HTTPRequest`
  - [createIssue](#createissue) (3 params) → `Object`
  - [getIssues](#getissues) (1 param) → `Collection`
  - [onError](#onerror) (2 params)
---

## 🏗️ Constructor

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

## ⚙️ Functions

### Regular Functions

#### newHttpRequest {#newhttprequest}


```4d
Function newHttpRequest($Url : Text; $Method : Text; $Body : Variant) -> 4D.HTTPRequest
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Url` | `Text` | - | - |
| `$Method` | `Text` | - | - |
| `$Body` | `Variant` | - | - |

**Returns:** `4D.HTTPRequest`

---

#### createIssue {#createissue}


```4d
Function createIssue($Title : Text; $Body : Text; $Labels : Collection) -> Object
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Title` | `Text` | - | - |
| `$Body` | `Text` | - | - |
| `$Labels` | `Collection` | - | - |

**Returns:** `Object`

---

#### getIssues {#getissues}


```4d
Function getIssues($Label : Text) -> Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Label` | `Text` | - | - |

**Returns:** `Collection`

---

#### onError {#onerror}


```4d
Function onError($HttpRequest : 4D.HTTPRequest; $Event : Object)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HttpRequest` | `4D.HTTPRequest` | - | - |
| `$Event` | `Object` | - | - |

---

---

*Generated from GitHubApi.4dm*
