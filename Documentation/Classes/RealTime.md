---
layout : default
title : RealTime
parent : Classes
---
# RealTime

📊 **Overview:** 5 Functions | 2 Getters

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T16:13:51.068Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (5):**

- [_getNextEvenHourBoundary](#_getnextevenhourboundary) (1 param) → `Real` 🖥️
- [_prepareSensorData](#_preparesensordata) (1 param) → `Collection` 🖥️
- [_createSingleCycle](#_createsinglecycle) (5 params) → `cs.RealTimeEntity` 🖥️
- [_createFragmentedCycles](#_createfragmentedcycles) (2 params) → `cs.RealTimeEntity` 🖥️
- [newFromJson](#newfromjson) (1 param) → `cs.RealTimeEntity` 🖥️

**🔍 Getters (2):**

- [TWO_HOURS_IN_SECONDS](#two_hours_in_seconds) → `Real`
- [SECONDS_IN_DAY](#seconds_in_day) → `Real`

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

### 🔍 Getters

#### TWO_HOURS_IN_SECONDS {#two_hours_in_seconds}
 `[🔍 getter]`

```4d
Function TWO_HOURS_IN_SECONDS -> Real
```

**Returns:** `Real`

---

#### SECONDS_IN_DAY {#seconds_in_day}
 `[🔍 getter]`

```4d
Function SECONDS_IN_DAY -> Real
```

**Returns:** `Real`

---

---

*Generated from RealTime.4dm*
