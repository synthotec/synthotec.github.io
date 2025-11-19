---
layout : default
title : RealTimeEntity
parent : Classes
---
# RealTimeEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeEntity.4dm)

📊 **Overview:** 1 Functions | 3 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T15:47:09.564Z*

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

Returns a collection of cs.RealTimeTemperatureSensor

**Returns:** `Collection`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### EndDateTime {#enddatetime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get EndDateTime -> cs.System.DateTime
```

**Returns:** `cs.System.DateTime`

---

#### MouldOpenTime {#mouldopentime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get MouldOpenTime -> Real
```

**Returns:** `Real`

---

#### StartTime {#starttime}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StartTime -> Time
```

**Returns:** `Time`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTime](../Tables/RealTime.md) - Source table for this ORDA class

---

*Generated from RealTimeEntity.4dm*
