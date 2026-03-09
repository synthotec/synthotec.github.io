---
layout : default
title : ToolTemperatureZone
parent : Classes
---
# ToolTemperatureZone [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureZone.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for temperature zone records, defining the named zones on injection moulding tools where temperature sensors are monitored. Supports entity migration with linking enabled by zone name.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.834Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns migration settings for ToolTemperatureZone with linking enabled and ordered by name

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolTemperatureZone](../Tables/ToolTemperatureZone.md) - ORDA DataClass class for ToolTemperatureZone table

### � Related Classes

- [ToolTemperatureZoneEntity](ToolTemperatureZoneEntity.md) - ORDA Entity class for ToolTemperatureZone table

### � Forms

- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from ToolTemperatureZone.4dm*
