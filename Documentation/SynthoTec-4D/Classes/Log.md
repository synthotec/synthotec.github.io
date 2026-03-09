---
layout : default
title : Log
parent : Classes
---
# Log [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Log.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

DataClass for application log entries, recording timestamped messages with process context. Provides a trim function to automatically delete old entries and keep the log within a configured maximum size.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:29.985Z*

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
