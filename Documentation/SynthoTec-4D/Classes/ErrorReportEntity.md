---
layout : default
title : ErrorReportEntity
parent : Classes
---
# ErrorReportEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ErrorReportEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:11.658Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [sendEmailReport](#sendemailreport)
    - [sendSlackReport](#sendslackreport) → `$Success : Boolean`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### sendEmailReport {#sendemailreport}


```4d
Function sendEmailReport
```

Sends email report for this error if SendEmail flag is enabled

---

#### sendSlackReport {#sendslackreport}


```4d
Function sendSlackReport -> $Success : Boolean
```

Sends formatted Slack report with error details, stack, call chain, and debug info if SendSlack flag is enabled

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ErrorReport](../Tables/ErrorReport.md) - ORDA Entity class for ErrorReport table

### � Related Classes

- [ErrorReport](ErrorReport.md) - ORDA DataClass class for ErrorReport table

---

*Generated from ErrorReportEntity.4dm*
