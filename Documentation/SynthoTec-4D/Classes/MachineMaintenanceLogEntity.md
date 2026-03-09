---
layout : default
title : MachineMaintenanceLogEntity
parent : Classes
---
# MachineMaintenanceLogEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MachineMaintenanceLogEntity.4dm)

📊 **Overview:** 2 Getters

## 📝 Description

Entity representing a machine maintenance log entry, with computed ISO timestamp and tab-separated timestamp properties that combine the maintenance date and time fields.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.990Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [TimeStamp](#timestamp) 🔍 → `Text`
    - [TimeStampWithTab](#timestampwithtab) 🔍 → `Text`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### TimeStamp {#timestamp}
 `[🔍 get only, 🖥️ local]`

```4d
Function get TimeStamp -> Text
```

Returns ISO timestamp string combining maintenance date and time

**Returns:** `Text`

---

#### TimeStampWithTab {#timestampwithtab}
 `[🔍 get only, 🖥️ local]`

```4d
Function get TimeStampWithTab -> Text
```

Returns timestamp with tab separator instead of T, truncated based on whether time is midnight

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [MachineMaintenanceLog](../Tables/MachineMaintenanceLog.md) - ORDA Entity class for MachineMaintenanceLog table

### � Forms

- [MachineMaintenance](../Forms/MachineMaintenance.md) - Data source for MachineMaintenance form

---

*Generated from MachineMaintenanceLogEntity.4dm*
