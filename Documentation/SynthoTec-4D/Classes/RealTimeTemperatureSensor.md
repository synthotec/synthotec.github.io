---
layout : default
title : RealTimeTemperatureSensor
parent : Classes
---
# RealTimeTemperatureSensor [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeTemperatureSensor.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 2 Getters

## 📝 Description

Creates temperature sensor object from sensor data, linking to tool temperature target if configured

🕐 *Last updated: 2026-01-13T16:04:13.286Z*

---

## 📑 Table of Contents

- [📋 Properties (5)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [InRange](#inrange) 🔍 → `Boolean`
    - [ZoneName](#zonename) 🔍 → `Text`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Index` | `Integer` | - | Sensor index number |
| `Zone` | `Integer` | - | Temperature zone ID this sensor monitors |
| `CelsiusValue` | `Real` | - | Current temperature reading in Celsius |
| `_WorksOrderEntity` | `cs.WorksOrderEntity` | - | Works order this sensor is monitoring |
| `ToolTemperatureTargetEntity` | `cs.ToolTemperatureTargetEntity` | - | Target temperature range for this zone, can be Null if not configured |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($WorksOrderEntity : cs.WorksOrderEntity; $TemperatureSensorObject : Object)
```

Creates temperature sensor object from sensor data, linking to tool temperature target if configured

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$WorksOrderEntity` | `cs.WorksOrderEntity` | - | - |
| `$TemperatureSensorObject` | `Object` | - | - |

---

## Functions {#functions}

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### InRange {#inrange}
 `[🔍 get only]`

```4d
Function get InRange -> Boolean
```

Returns true if temperature is within target range, Null if no target configured

**Returns:** `Boolean`

---

#### ZoneName {#zonename}
 `[🔍 get only]`

```4d
Function get ZoneName -> Text
```

Returns the name of the temperature zone from ToolTemperatureZone table

**Returns:** `Text`

---

---

*Generated from RealTimeTemperatureSensor.4dm*
