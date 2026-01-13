---
layout : default
title : Log
parent : Classes
---
# Log [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Log.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:12.088Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [record](#record) (2 params) 🖥️
    - [trim](#trim)
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### record {#record}
 `[🖥️ local]`

```4d
Function record($Message : Text; $RecordMessage : Boolean)
```

Records a log message with timestamp and process info, optionally can be disabled with $RecordMessage=False

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Message` | `Text` | - | - |
| `$RecordMessage` | `Boolean` | - | - |

---

#### trim {#trim}


```4d
Function trim
```

Deletes old log entries to keep total log size within configured limit (default 10000 entries)

---

## Related Items {#related-items}

### 🗂️ Tables

- [Log](../Tables/Log.md) - ORDA DataClass class for Log table

---

*Generated from Log.4dm*
