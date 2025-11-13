---
layout : default
title : ToolTemperatureTargetSelection
parent : Classes
---
# ToolTemperatureTargetSelection

📊 **Overview:** 2 Functions

**Extends:** `EntitySelection`

🕐 *Last updated: 2025-11-13T21:44:56.248Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [CheckInRange](#checkinrange) (1 param) → `Boolean`
- [CheckTargetsSet](#checktargetsset) (1 param) → `Boolean`

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (3)

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

## 🔗 Related Items

### 🗂️ Tables

- [ToolTemperatureTarget](../Tables/ToolTemperatureTarget.md) - Source table for this ORDA class
- [ToolTemperatureTarget](../Tables/ToolTemperatureTarget.md) - Database table storing ToolTemperatureTarget records

### � Related Classes

- [ToolTemperatureTarget](ToolTemperatureTarget.md) - ORDA DataClass class for ToolTemperatureTarget table
- [ToolTemperatureTargetEntity](ToolTemperatureTargetEntity.md) - ORDA Entity class for ToolTemperatureTarget table
- [ToolTemperatureTargetSelection](ToolTemperatureTargetSelection.md) - ORDA EntitySelection class for ToolTemperatureTarget table

---

*Generated from ToolTemperatureTargetSelection.4dm*
