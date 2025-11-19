---
layout : default
title : RealTimeTemperatureSensor
parent : Classes
---
# RealTimeTemperatureSensor [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeTemperatureSensor.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 2 Getters

🕐 *Last updated: 2025-11-19T15:47:09.726Z*

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
| `Index` | `Integer` | - | - |
| `Zone` | `Integer` | - | - |
| `CelsiusValue` | `Real` | - | - |
| `_WorksOrderEntity` | `cs.WorksOrderEntity` | - | - |
| `ToolTemperatureTargetEntity` | `cs.ToolTemperatureTargetEntity` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($WorksOrderEntity : cs.WorksOrderEntity; $TemperatureSensorObject : Object)
```

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

**Returns:** `Boolean`

---

#### ZoneName {#zonename}
 `[🔍 get only]`

```4d
Function get ZoneName -> Text
```

**Returns:** `Text`

---

---

*Generated from RealTimeTemperatureSensor.4dm*
