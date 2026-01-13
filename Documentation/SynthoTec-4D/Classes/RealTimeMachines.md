---
layout : default
title : RealTimeMachines
parent : Classes
---
# RealTimeMachines [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeMachines.4dm)

📊 **Overview:** 1 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:13.092Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getByMachine](#getbymachine) (1 param) → `cs.RealTimeMachinesEntity`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getByMachine {#getbymachine}


```4d
Function getByMachine($MachineNumber : Integer) -> cs.RealTimeMachinesEntity
```

Returns the RealTime machine entity for the specified machine number

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MachineNumber` | `Integer` | - | - |

**Returns:** `cs.RealTimeMachinesEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTimeMachines](../Tables/RealTimeMachines.md) - ORDA DataClass class for RealTimeMachines table

### � Related Classes

- [RealTimeMachinesEntity](RealTimeMachinesEntity.md) - ORDA Entity class for RealTimeMachines table

### � Forms

- [CurrentDownTime](../Forms/CurrentDownTime.md) - Data source for CurrentDownTime form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [MachineMaintenance](../Forms/MachineMaintenance.md) - Data source for MachineMaintenance form
- [RealTimeMonitor](../Forms/RealTimeMonitor.md) - Data source for RealTimeMonitor form
- [RealTimeViewer](../Forms/RealTimeViewer.md) - Data source for RealTimeViewer form
- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form

---

*Generated from RealTimeMachines.4dm*
