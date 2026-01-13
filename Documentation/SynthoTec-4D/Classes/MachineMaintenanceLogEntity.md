---
layout : default
title : MachineMaintenanceLogEntity
parent : Classes
---
# MachineMaintenanceLogEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MachineMaintenanceLogEntity.4dm)

📊 **Overview:** 2 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:12.093Z*

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
