---
layout : default
title : RealTimeEntity
parent : Classes
---
# RealTimeEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeEntity.4dm)

📊 **Overview:** 1 Functions | 3 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:13.087Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getTemperatureSensors](#gettemperaturesensors) → `$TemperatureSensors : Collection` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [EndDateTime](#enddatetime) 🔍 → `cs.System.DateTime`
    - [MouldOpenTime](#mouldopentime) 🔍 → `Real`
    - [StartTime](#starttime) 🔍 → `Time`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getTemperatureSensors {#gettemperaturesensors}
 `[🖥️ local]`

```4d
Function getTemperatureSensors -> $TemperatureSensors : Collection
```

Returns collection of RealTimeTemperatureSensor objects parsed from sensor data; empty collection if no sensor data available

**Returns:** `Collection`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### EndDateTime {#enddatetime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get EndDateTime -> cs.System.DateTime
```

Returns end date-time as System.DateTime object for cycle record; combines end date and end time properties

**Returns:** `cs.System.DateTime`

---

#### MouldOpenTime {#mouldopentime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get MouldOpenTime -> Real
```

Returns time in seconds that mould was open during this cycle (total cycle time minus mould closed time)

**Returns:** `Real`

---

#### StartTime {#starttime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StartTime -> Time
```

Returns start time of cycle; calculates by subtracting cycle time from end time; returns 00:00:00 if result negative

**Returns:** `Time`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - ORDA Entity class for RealTime table

### � Related Classes

- [RealTime](RealTime.md) - ORDA DataClass class for RealTime table
- [RealTimeSelection](RealTimeSelection.md) - ORDA EntitySelection class for RealTime table

### � Forms

- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from RealTimeEntity.4dm*
