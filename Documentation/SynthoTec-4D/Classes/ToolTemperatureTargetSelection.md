---
layout : default
title : ToolTemperatureTargetSelection
parent : Classes
---
# ToolTemperatureTargetSelection [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolTemperatureTargetSelection.4dm)

📊 **Overview:** 2 Functions

**Extends:** `EntitySelection`

🕐 *Last updated: 2025-12-10T11:45:24.524Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [CheckInRange](#checkinrange) (1 param) → `Boolean`
    - [CheckTargetsSet](#checktargetsset) (1 param) → `Boolean`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### CheckInRange {#checkinrange}


```4d
Function CheckInRange($TemperatureSensorCollection : Collection) -> Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$TemperatureSensorCollection` | `Collection` | - | - |

**Returns:** `Boolean`

---

#### CheckTargetsSet {#checktargetsset}


```4d
Function CheckTargetsSet($RealTimeMachinesEntity : cs.RealTimeMachinesEntity) -> Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | - |

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolTemperatureTarget](../Tables/ToolTemperatureTarget.md) - ORDA EntitySelection class for ToolTemperatureTarget table

### � Related Classes

- [ToolTemperatureTarget](ToolTemperatureTarget.md) - ORDA DataClass class for ToolTemperatureTarget table
- [ToolTemperatureTargetEntity](ToolTemperatureTargetEntity.md) - ORDA Entity class for ToolTemperatureTarget table

### � Forms

- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from ToolTemperatureTargetSelection.4dm*
