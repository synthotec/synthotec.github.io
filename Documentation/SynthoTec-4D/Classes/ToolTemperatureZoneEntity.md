---
layout : default
title : ToolTemperatureZoneEntity
parent : Classes
---
# ToolTemperatureZoneEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureZoneEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a named temperature zone on a tool (e.g., Zone 1, Nozzle). Supports migration synchronisation that fills blank zone names from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:31.839Z*

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

Returns migration rules for syncing temperature zone data during migration

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

Syncs related temperature target entities during data migration (currently commented out)

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
