# RealTime

**Extends:** `DataClass`

## Table of Contents

### Functions

- [TWO_HOURS_IN_SECONDS() [getter]](#two_hours_in_seconds)
- [SECONDS_IN_DAY() [getter]](#seconds_in_day)
- [_getNextEvenHourBoundary()](#_getnextevenhourboundary)
- [_prepareSensorData()](#_preparesensordata)
- [_createSingleCycle()](#_createsinglecycle)
- [_createFragmentedCycles()](#_createfragmentedcycles)
- [newFromJson()](#newfromjson)

---

## Functions

### TWO_HOURS_IN_SECONDS {#two_hours_in_seconds}
 `[exposed]` `[getter]`

```4d
Function TWO_HOURS_IN_SECONDS -> Real
```

**Returns:** `Real`

---

### SECONDS_IN_DAY {#seconds_in_day}
 `[exposed]` `[getter]`

```4d
Function SECONDS_IN_DAY -> Real
```

**Returns:** `Real`

---

### _getNextEvenHourBoundary {#_getnextevenhourboundary}
 `[local]`

```4d
Function _getNextEvenHourBoundary($FromTimeSeconds : Real) -> Real
```

Get the next even hour boundary (00:00, 02:00, 04:00, etc.)

**Returns:** `Real`

---

### _prepareSensorData {#_preparesensordata}
 `[local]`

```4d
Function _prepareSensorData($RealTimeCycleObject : Object) -> Collection
```

Prepare sensor data collection once for reuse across fragments

**Returns:** `Collection`

---

### _createSingleCycle {#_createsinglecycle}
 `[local]`

```4d
Function _createSingleCycle($RealTimeCycleObject : Object; $SensorData : Collection; $OverrideCycleTime : Real; $OverrideEndDate : Date; $OverrideEndTimeSeconds : Real) -> cs.RealTimeEntity
```

Create a single cycle record

**Returns:** `cs.RealTimeEntity`

---

### _createFragmentedCycles {#_createfragmentedcycles}
 `[local]`

```4d
Function _createFragmentedCycles($RealTimeCycleObject : Object; $SensorData : Collection) -> cs.RealTimeEntity
```

Create fragmented cycles split at even hour boundaries

**Returns:** `cs.RealTimeEntity`

---

### newFromJson {#newfromjson}
 `[local]`

```4d
Function newFromJson($Json : Text) -> cs.RealTimeEntity
```

**Returns:** `cs.RealTimeEntity`

---

---

*Generated from RealTime.4dm*
*Last updated: 2025-11-12T17:17:32.240Z*
