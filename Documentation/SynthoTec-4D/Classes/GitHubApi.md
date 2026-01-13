---
layout : default
title : GitHubApi
parent : Classes
---
# GitHubApi [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/GitHubApi.4dm)

📊 **Overview:** 1 Constructor | 4 Functions

## 📝 Description

Create a new HTTP request with GitHub API headers and authentication

🕐 *Last updated: 2026-01-13T16:04:11.955Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [newHttpRequest](#newhttprequest) (3 params) → `4D.HTTPRequest`
    - [createIssue](#createissue) (3 params) → `Object`
    - [getIssues](#getissues) (1 param) → `Collection`
    - [onError](#onerror) (2 params)

---

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Initialize GitHub API wrapper for repository operations

---

## Functions {#functions}

### Regular Functions

#### newHttpRequest {#newhttprequest}


```4d
Function newHttpRequest($Url : Text; $Method : Text; $Body : Variant) -> 4D.HTTPRequest
```

Create a new HTTP request with GitHub API headers and authentication

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

Create a new GitHub issue with title, body, and optional labels

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

Retrieve all GitHub issues, optionally filtered by label

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

Handle HTTP request errors (callback function)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HttpRequest` | `4D.HTTPRequest` | - | - |
| `$Event` | `Object` | - | - |

---

---

*Generated from GitHubApi.4dm*
