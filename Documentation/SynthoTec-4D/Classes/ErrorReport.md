---
layout : default
title : ErrorReport
parent : Classes
---
# ErrorReport [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ErrorReport.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for error report records, capturing the full 4D error stack, call chain, debug variables, and component codes at the time of an error using the legacy error stack API.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:29.592Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [processError](#processerror) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### processError {#processerror}
 `[🖥️ local]`

```4d
Function processError
```

Processes current 4D error by creating error object with stack, call chain, and debug info, then saves to database

---

## Related Items {#related-items}

### 🗂️ Tables

- [ErrorReport](../Tables/ErrorReport.md) - ORDA DataClass class for ErrorReport table

### � Related Classes

- [ErrorReportEntity](ErrorReportEntity.md) - ORDA Entity class for ErrorReport table

---

*Generated from ErrorReport.4dm*
