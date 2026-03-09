---
layout : default
title : PrintJobEntity
parent : Classes
---
# PrintJobEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PrintJobEntity.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

Entity representing a queued print job, storing the printer, paper name, orientation, and number of copies. Executes the job by opening a 4D printing session and rendering the required number of copies.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.617Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [print](#print) → `$Success : Boolean` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### print {#print}
 `[🖥️ local]`

```4d
Function print -> $Success : Boolean
```

Prints this print job by opening a printing job, rendering copies, and marking as printed

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [PrintJob](../Tables/PrintJob.md) - ORDA Entity class for PrintJob table

---

*Generated from PrintJobEntity.4dm*
