---
layout : default
title : ToolTemperatureTarget
parent : Classes
---
# ToolTemperatureTarget [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureTarget.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

DataClass for tool temperature target records, defining the acceptable min/max temperature range for each zone on a tool. Provides a lookup by works order that resolves the machine's configured temperature zones.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.807Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getByWorksOrder](#getbyworksorder) (1 param) → `cs.ToolTemperatureTargetSelection`
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getByWorksOrder {#getbyworksorder}


```4d
Function getByWorksOrder($WorksOrder : Integer) -> cs.ToolTemperatureTargetSelection
```

Returns temperature targets for zones configured on the machine running the specified works order

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$WorksOrder` | `Integer` | - | - |

**Returns:** `cs.ToolTemperatureTargetSelection`

---

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns configuration for entity migration, linking is disabled for this table

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolTemperatureTarget](../Tables/ToolTemperatureTarget.md) - ORDA DataClass class for ToolTemperatureTarget table

### � Related Classes

- [ToolTemperatureTargetEntity](ToolTemperatureTargetEntity.md) - ORDA Entity class for ToolTemperatureTarget table
- [ToolTemperatureTargetSelection](ToolTemperatureTargetSelection.md) - ORDA EntitySelection class for ToolTemperatureTarget table

### � Forms

- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from ToolTemperatureTarget.4dm*
