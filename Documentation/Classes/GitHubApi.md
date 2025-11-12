# GitHubApi

## Table of Contents

### Functions

- [newHttpRequest()](#newhttprequest)
- [createIssue()](#createissue)
- [getIssues()](#getissues)
- [onError()](#onerror)

---

## Functions

### newHttpRequest {#newhttprequest}


```4d
Function newHttpRequest($Url : Text; $Method : Text; $Body : Variant) -> 4D.HTTPRequest
```

**Returns:** `4D.HTTPRequest`

---

### createIssue {#createissue}


```4d
Function createIssue($Title : Text; $Body : Text; $Labels : Collection) -> Object
```

**Returns:** `Object`

---

### getIssues {#getissues}


```4d
Function getIssues($Label : Text) -> Collection
```

**Returns:** `Collection`

---

### onError {#onerror}


```4d
Function onError($HttpRequest : 4D.HTTPRequest; $Event : Object)
```

---

---

*Generated from GitHubApi.4dm*
*Last updated: 2025-11-12T17:04:21.789Z*
