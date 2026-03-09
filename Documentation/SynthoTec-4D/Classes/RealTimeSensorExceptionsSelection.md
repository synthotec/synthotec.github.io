---
layout : default
title : RealTimeSensorExceptionsSelection
parent : Classes
---
# RealTimeSensorExceptionsSelection [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeSensorExceptionsSelection.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

Entity selection of temperature sensor exception records, providing batch acknowledgement by locking all associated works orders to prevent modification of acknowledged exceptions.

**Extends:** `EntitySelection`

🕐 *Last updated: 2026-03-09T14:45:31.176Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [acknowledge](#acknowledge) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### acknowledge {#acknowledge}
 `[🖥️ local]`

```4d
Function acknowledge
```

Acknowledges sensor exceptions by locking associated works orders to prevent modification

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTimeSensorExceptions](../Tables/RealTimeSensorExceptions.md) - ORDA EntitySelection class for RealTimeSensorExceptions table

### � Related Classes

- [RealTimeSensorExceptionsEntity](RealTimeSensorExceptionsEntity.md) - ORDA Entity class for RealTimeSensorExceptions table

---

*Generated from RealTimeSensorExceptionsSelection.4dm*
