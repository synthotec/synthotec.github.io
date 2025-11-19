---
layout : default
title : ToolTemperatureZoneEntity
parent : Classes
---
# ToolTemperatureZoneEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureZoneEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T21:53:04.530Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ToolTemperatureZoneEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolTemperatureZoneEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ToolTemperatureZoneEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolTemperatureZoneEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolTemperatureZone](../Tables/ToolTemperatureZone.md) - ORDA Entity class for ToolTemperatureZone table

### � Related Classes

- [ToolTemperatureZone](ToolTemperatureZone.md) - ORDA DataClass class for ToolTemperatureZone table

### � Forms

- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from ToolTemperatureZoneEntity.4dm*
