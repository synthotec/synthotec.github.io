---
layout : default
title : RealTimeSensorExceptionsEntity
parent : Classes
---
# RealTimeSensorExceptionsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeSensorExceptionsEntity.4dm)

📊 **Overview:** 3 Functions | 4 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-20T14:23:50.452Z*

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

**Returns:** `cs.RealTimeSelection`

---

#### getTemperatureSensors {#gettemperaturesensors}
 `[🖥️ local]`

```4d
Function getTemperatureSensors($Zone : Integer) -> Collection
```

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

**Returns:** `Boolean`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Duration {#duration}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Duration -> Time
```

**Returns:** `Time`

---

#### HighestCelciusTemperature {#highestcelciustemperature}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HighestCelciusTemperature -> Real
```

**Returns:** `Real`

---

#### LowestCelciusTemperature {#lowestcelciustemperature}
 `[🔍 get only, 🖥️ local]`

```4d
Function get LowestCelciusTemperature -> Real
```

**Returns:** `Real`

---

#### PartsMade {#partsmade}
 `[🔍 get only, 🖥️ local]`

```4d
Function get PartsMade -> Integer
```

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTimeSensorExceptions](../Tables/RealTimeSensorExceptions.md) - ORDA Entity class for RealTimeSensorExceptions table

### � Related Classes

- [RealTimeSensorExceptionsSelection](RealTimeSensorExceptionsSelection.md) - ORDA EntitySelection class for RealTimeSensorExceptions table

---

*Generated from RealTimeSensorExceptionsEntity.4dm*
