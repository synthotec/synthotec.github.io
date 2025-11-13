---
layout : default
title : RealTimeTemperatureSensor
parent : Classes
---
# RealTimeTemperatureSensor

📊 **Overview:** 5 Properties | 1 Constructor | 2 Getters

🕐 *Last updated: 2025-11-13T13:29:03.397Z*

---

## 📑 Table of Contents

### 📋 Properties (5)

- [Index](#index) : `Integer`
- [Zone](#zone) : `Integer`
- [CelsiusValue](#celsiusvalue) : `Real`
- [_WorksOrderEntity](#worksorderentity) : `cs.WorksOrderEntity`
- [ToolTemperatureTargetEntity](#tooltemperaturetargetentity) : `cs.ToolTemperatureTargetEntity`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**🔍 Getters (2):**

- [ZoneName](#zonename) → `Text`
- [InRange](#inrange) → `Boolean`

### 🔗 Related Items

- [Classes](#-related-classes) (1)

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

## 🔗 Related Items

### 📦 Related Classes

- [](.md) - Extends this class

---

*Generated from RealTimeTemperatureSensor.4dm*
