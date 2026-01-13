---
layout : default
title : RealTimeSensorExceptionsEntity
parent : Classes
---
# RealTimeSensorExceptionsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeSensorExceptionsEntity.4dm)

📊 **Overview:** 3 Functions | 4 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:13.269Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getRealTimeSelection](#getrealtimeselection) → `cs.RealTimeSelection` 🖥️
    - [getTemperatureSensors](#gettemperaturesensors) (1 param) → `Collection` 🖥️
    - [sendEmail](#sendemail) → `Boolean`
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Duration](#duration) 🔍 → `Time`
    - [HighestCelciusTemperature](#highestcelciustemperature) 🔍 → `Real`
    - [LowestCelciusTemperature](#lowestcelciustemperature) 🔍 → `Real`
    - [PartsMade](#partsmade) 🔍 → `Integer`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getRealTimeSelection {#getrealtimeselection}
 `[🖥️ local]`

```4d
Function getRealTimeSelection -> cs.RealTimeSelection
```

Queries RealTime table for all records within this exception's ID range and matching works order; returns entity selection used by other methods to aggregate data

**Returns:** `cs.RealTimeSelection`

---

#### getTemperatureSensors {#gettemperaturesensors}
 `[🖥️ local]`

```4d
Function getTemperatureSensors($Zone : Integer) -> Collection
```

Returns collection of temperature sensor readings (from RealTime records) for specified zone, or all zones if $Zone not provided; filters based on this exception's real-time records

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Zone` | `Integer` | - | - |

**Returns:** `Collection`

---

#### sendEmail {#sendemail}


```4d
Function sendEmail -> Boolean
```

Builds and sends HTML email with temperature exception details including works order, machine, tool, affected zones, and temperature readings; returns success boolean; creates table showing min/max temperatures with pass/fail coloring

**Returns:** `Boolean`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Duration {#duration}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Duration -> Time
```

Returns total cycle time for this exception's real-time records converted to Time format; aggregates CycleTime between FirstRealTimeID and LastRealTimeID

**Returns:** `Time`

---

#### HighestCelciusTemperature {#highestcelciustemperature}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HighestCelciusTemperature -> Real
```

Returns maximum temperature (in Celsius) recorded across all sensors during this exception's real-time records; returns 0 if no sensor data available

**Returns:** `Real`

---

#### LowestCelciusTemperature {#lowestcelciustemperature}
 `[🔍 get only, 🖥️ local]`

```4d
Function get LowestCelciusTemperature -> Real
```

Returns minimum temperature (in Celsius) recorded across all sensors during this exception's real-time records; returns 0 if no sensor data available

**Returns:** `Real`

---

#### PartsMade {#partsmade}
 `[🔍 get only, 🖥️ local]`

```4d
Function get PartsMade -> Integer
```

Returns total impressions (parts produced) for this temperature exception's real-time records; aggregates from all records between FirstRealTimeID and LastRealTimeID

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTimeSensorExceptions](../Tables/RealTimeSensorExceptions.md) - ORDA Entity class for RealTimeSensorExceptions table

### � Related Classes

- [RealTimeSensorExceptionsSelection](RealTimeSensorExceptionsSelection.md) - ORDA EntitySelection class for RealTimeSensorExceptions table

---

*Generated from RealTimeSensorExceptionsEntity.4dm*
