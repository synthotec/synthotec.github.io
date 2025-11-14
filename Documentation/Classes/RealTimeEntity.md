---
layout : default
title : RealTimeEntity
parent : Classes
---
# RealTimeEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeEntity.4dm)

📊 **Overview:** 1 Functions | 3 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:18:21.120Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [getTemperatureSensors](#gettemperaturesensors) → `$TemperatureSensors : Collection` 🖥️
  - [MouldOpenTime](#mouldopentime) → `Real`
  - [StartTime](#starttime) → `Time`
  - [EndDateTime](#enddatetime) → `cs.System.DateTime`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### getTemperatureSensors {#gettemperaturesensors}
 `[🖥️ local]`

```4d
Function getTemperatureSensors -> $TemperatureSensors : Collection
```

Returns a collection of cs.RealTimeTemperatureSensor

**Returns:** `Collection`

---

### Getters

#### MouldOpenTime {#mouldopentime}
 `[🖥️ local, 🔍 getter]`

```4d
Function MouldOpenTime -> Real
```

**Returns:** `Real`

---

#### StartTime {#starttime}
 `[🖥️ local, 🔍 getter]`

```4d
Function StartTime -> Time
```

**Returns:** `Time`

---

#### EndDateTime {#enddatetime}
 `[🖥️ local, 🔍 getter]`

```4d
Function EndDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - Source table for this ORDA class

### � Related Classes

- [RealTime](RealTime.md) - ORDA DataClass class for RealTime table
- [RealTimeSelection](RealTimeSelection.md) - ORDA EntitySelection class for RealTime table

---

*Generated from RealTimeEntity.4dm*
