---
layout : default
title : RealTimeTemperatureSensor
parent : Classes
---
# RealTimeTemperatureSensor

📊 **Overview:** 5 Properties | 1 Constructor | 2 Getters

🕐 *Last updated: 2025-11-13T02:24:48.782Z*

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

---

## 📋 Properties

### Quick Reference

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Index` | `Integer` | - |  |
| `Zone` | `Integer` | - |  |
| `CelsiusValue` | `Real` | - |  |
| `_WorksOrderEntity` | `cs.WorksOrderEntity` | - |  |
| `ToolTemperatureTargetEntity` | `cs.ToolTemperatureTargetEntity` | - |  |

### Detailed Information

#### Index {#index}

**Type:** `Integer`

---

#### Zone {#zone}

**Type:** `Integer`

---

#### CelsiusValue {#celsiusvalue}

**Type:** `Real`

---

#### _WorksOrderEntity {#worksorderentity}

**Type:** `cs.WorksOrderEntity`

---

#### ToolTemperatureTargetEntity {#tooltemperaturetargetentity}

**Type:** `cs.ToolTemperatureTargetEntity`

---

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
