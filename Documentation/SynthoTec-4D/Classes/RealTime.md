---
layout : default
title : RealTime
parent : Classes
---
# RealTime [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTime.4dm)

📊 **Overview:** 5 Functions | 2 Getters

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T16:53:01.214Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [_getNextEvenHourBoundary](#_getnextevenhourboundary) (1 param) → `Real` 🖥️
    - [_prepareSensorData](#_preparesensordata) (1 param) → `Collection` 🖥️
    - [_createSingleCycle](#_createsinglecycle) (5 params) → `cs.RealTimeEntity` 🖥️
    - [_createFragmentedCycles](#_createfragmentedcycles) (2 params) → `cs.RealTimeEntity` 🖥️
    - [newFromJson](#newfromjson) (1 param) → `cs.RealTimeEntity` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [SECONDS_IN_DAY](#seconds_in_day) 🔍 → `Real`
    - [TWO_HOURS_IN_SECONDS](#two_hours_in_seconds) 🔍 → `Real`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### _getNextEvenHourBoundary {#_getnextevenhourboundary}
 `[🖥️ local]`

```4d
Function _getNextEvenHourBoundary($FromTimeSeconds : Real) -> Real
```

Get the next even hour boundary (00:00, 02:00, 04:00, etc.)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FromTimeSeconds` | `Real` | - | - |

**Returns:** `Real`

---

#### _prepareSensorData {#_preparesensordata}
 `[🖥️ local]`

```4d
Function _prepareSensorData($RealTimeCycleObject : Object) -> Collection
```

Prepare sensor data collection once for reuse across fragments

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeCycleObject` | `Object` | - | - |

**Returns:** `Collection`

---

#### _createSingleCycle {#_createsinglecycle}
 `[🖥️ local]`

```4d
Function _createSingleCycle($RealTimeCycleObject : Object; $SensorData : Collection; $OverrideCycleTime : Real; $OverrideEndDate : Date; $OverrideEndTimeSeconds : Real) -> cs.RealTimeEntity
```

Create a single cycle record

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeCycleObject` | `Object` | - | - |
| `$SensorData` | `Collection` | - | - |
| `$OverrideCycleTime` | `Real` | - | - |
| `$OverrideEndDate` | `Date` | - | - |
| `$OverrideEndTimeSeconds` | `Real` | - | - |

**Returns:** `cs.RealTimeEntity`

---

#### _createFragmentedCycles {#_createfragmentedcycles}
 `[🖥️ local]`

```4d
Function _createFragmentedCycles($RealTimeCycleObject : Object; $SensorData : Collection) -> cs.RealTimeEntity
```

Create fragmented cycles split at even hour boundaries

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeCycleObject` | `Object` | - | - |
| `$SensorData` | `Collection` | - | - |

**Returns:** `cs.RealTimeEntity`

---

#### newFromJson {#newfromjson}
 `[🖥️ local]`

```4d
Function newFromJson($Json : Text) -> cs.RealTimeEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Json` | `Text` | - | - |

**Returns:** `cs.RealTimeEntity`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### SECONDS_IN_DAY {#seconds_in_day}
 `[🔍 get only]`

```4d
Function get SECONDS_IN_DAY -> Real
```

**Returns:** `Real`

---

#### TWO_HOURS_IN_SECONDS {#two_hours_in_seconds}
 `[🔍 get only]`

```4d
Function get TWO_HOURS_IN_SECONDS -> Real
```

**Returns:** `Real`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - Source table for this ORDA class

### � Related Classes

- [RealTimeEntity](RealTimeEntity.md) - ORDA Entity class for RealTime table
- [RealTimeSelection](RealTimeSelection.md) - ORDA EntitySelection class for RealTime table

---

*Generated from RealTime.4dm*
