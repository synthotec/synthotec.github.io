---
layout : default
title : Error
parent : Classes
---
# Error [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Error.4dm)

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-12-10T11:45:22.829Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [fillGitHubIssues](#fillgithubissues)
    - [setDebugInfo](#setdebuginfo) (1 param) 🖥️
    - [notify](#notify)
    - [record](#record) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### fillGitHubIssues {#fillgithubissues}


```4d
Function fillGitHubIssues
```

Fetches and associates GitHub issues with error entities using issue labels

---

#### setDebugInfo {#setdebuginfo}
 `[🖥️ local]`

```4d
Function setDebugInfo(...)
```

Sets debug information for error tracking using variable number of parameters

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `...` | *Not specified* | - | - |

---

#### notify {#notify}


```4d
Function notify
```

Sends email notification for new unsuppressed errors since last notification (once per hour)

---

#### record {#record}
 `[🖥️ local]`

```4d
Function record
```

Records error information by creating MD5 digest of error details for deduplication

---

## Related Items {#related-items}

### 🗂️ Tables

- [Error](../Tables/Error.md) - ORDA DataClass class for Error table

### � Related Classes

- [ErrorEntity](ErrorEntity.md) - ORDA Entity class for Error table

### � Forms

- [Errors](../Forms/Errors.md) - Data source for Errors form

---

*Generated from Error.4dm*
