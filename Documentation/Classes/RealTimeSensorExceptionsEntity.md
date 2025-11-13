---
layout : default
title : RealTimeSensorExceptionsEntity
parent : Classes
---
# RealTimeSensorExceptionsEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeSensorExceptionsEntity.4dm)

📊 **Overview:** 3 Functions | 4 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T23:49:47.402Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#️-functions)
  - [getRealTimeSelection](#getrealtimeselection) → `cs.RealTimeSelection` 🖥️
  - [getTemperatureSensors](#gettemperaturesensors) (1 param) → `Collection` 🖥️
  - [sendEmail](#sendemail) → `Boolean`
  - [PartsMade](#partsmade) → `Integer`
  - [Duration](#duration) → `Time`
  - [LowestCelciusTemperature](#lowestcelciustemperature) → `Real`
  - [HighestCelciusTemperature](#highestcelciustemperature) → `Real`
- [🔗 Related Items](#-related-items)
---

## ⚙️ Functions

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

#### PartsMade {#partsmade}
 `[🖥️ local, 🔍 getter]`

```4d
Function PartsMade -> Integer
```

**Returns:** `Integer`

---

#### Duration {#duration}
 `[🖥️ local, 🔍 getter]`

```4d
Function Duration -> Time
```

**Returns:** `Time`

---

#### LowestCelciusTemperature {#lowestcelciustemperature}
 `[🖥️ local, 🔍 getter]`

```4d
Function LowestCelciusTemperature -> Real
```

**Returns:** `Real`

---

#### HighestCelciusTemperature {#highestcelciustemperature}
 `[🖥️ local, 🔍 getter]`

```4d
Function HighestCelciusTemperature -> Real
```

**Returns:** `Real`

---

## 🔗 Related Items

### 🗂️ Tables

- [RealTimeSensorExceptions](../Tables/RealTimeSensorExceptions.md) - Source table for this ORDA class

### � Related Classes

- [RealTimeSensorExceptionsSelection](RealTimeSensorExceptionsSelection.md) - ORDA EntitySelection class for RealTimeSensorExceptions table

---

*Generated from RealTimeSensorExceptionsEntity.4dm*
