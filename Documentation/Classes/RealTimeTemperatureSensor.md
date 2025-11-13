---
layout : default
title : RealTimeTemperatureSensor
parent : Classes
---
# RealTimeTemperatureSensor [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeTemperatureSensor.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 2 Getters

🕐 *Last updated: 2025-11-13T23:29:28.540Z*

---

## 📑 Table of Contents

- [📋 Properties (5)](#-properties)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**🔍 Getters (2):**

- [ZoneName](#zonename) → `Text`
- [InRange](#inrange) → `Boolean`

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Index` | `Integer` | - | - |
| `Zone` | `Integer` | - | - |
| `CelsiusValue` | `Real` | - | - |
| `_WorksOrderEntity` | `cs.WorksOrderEntity` | - | - |
| `ToolTemperatureTargetEntity` | `cs.ToolTemperatureTargetEntity` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

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

### 🔍 Getters

#### ZoneName {#zonename}
 `[🔍 getter]`

```4d
Function ZoneName -> Text
```

**Returns:** `Text`

---

#### InRange {#inrange}
 `[🔍 getter]`

```4d
Function InRange -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from RealTimeTemperatureSensor.4dm*
