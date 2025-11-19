---
layout : default
title : ToolTemperatureTargetEntity
parent : Classes
---
# ToolTemperatureTargetEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureTargetEntity.4dm)

📊 **Overview:** 3 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T18:12:03.888Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [SetTargetValues](#settargetvalues) (1 param) 🖥️
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### SetTargetValues {#settargetvalues}
 `[🖥️ local]`

```4d
Function SetTargetValues($ToolsEntity : cs.ToolsEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ToolTemperatureTargetEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolTemperatureTargetEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ToolTemperatureTargetEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ToolTemperatureTargetEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolTemperatureTarget](../Tables/ToolTemperatureTarget.md) - ORDA Entity class for ToolTemperatureTarget table

### � Related Classes

- [ToolTemperatureTarget](ToolTemperatureTarget.md) - ORDA DataClass class for ToolTemperatureTarget table
- [ToolTemperatureTargetSelection](ToolTemperatureTargetSelection.md) - ORDA EntitySelection class for ToolTemperatureTarget table

### � Forms

- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from ToolTemperatureTargetEntity.4dm*
