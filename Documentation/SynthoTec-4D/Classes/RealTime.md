---
layout : default
title : RealTime
parent : Classes
---
# RealTime [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTime.4dm)

📊 **Overview:** 5 Functions | 2 Getters

## 📝 Description

DataClass for real-time production cycle records captured from injection moulding machines. Provides time boundary constants and cycle fragmentation helpers for splitting long cycles at even-hour boundaries.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.971Z*

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

Calculates next even hour boundary (00, 02, 04, etc.) in seconds; used for cycle fragmentation

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

Extracts and validates temperature sensor data from cycle object; filters by machine's configured temperature zones

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

Creates and saves a single RealTime cycle record with optional override parameters for fragmented cycles

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

Splits long cycles (>2 hours) into multiple records at even hour boundaries; returns last created entity

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

Parses JSON cycle data and creates RealTime entity; automatically fragments cycles longer than 2 hours

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

Returns constant value 86400 (seconds in a day for midnight wraparound calculations)

**Returns:** `Real`

---

#### TWO_HOURS_IN_SECONDS {#two_hours_in_seconds}
 `[🔍 get only]`

```4d
Function get TWO_HOURS_IN_SECONDS -> Real
```

Returns constant value 7200 (two hours in seconds for cycle fragmentation boundaries)

**Returns:** `Real`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - ORDA DataClass class for RealTime table

### � Related Classes

- [RealTimeEntity](RealTimeEntity.md) - ORDA Entity class for RealTime table
- [RealTimeSelection](RealTimeSelection.md) - ORDA EntitySelection class for RealTime table

### � Forms

- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from RealTime.4dm*
