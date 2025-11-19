---
layout : default
title : RealTimeMachinesEntity
parent : Classes
---
# RealTimeMachinesEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeMachinesEntity.4dm)

📊 **Overview:** 1 Functions | 6 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T21:53:03.910Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [checkTempZoneExists](#checktempzoneexists) (1 param) → `Boolean`
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [AssignedTemperatureSensorsPresent](#assignedtemperaturesensorspresent) 🔍 → `Boolean`
    - [Changing](#changing) 🔍 → `Boolean`
    - [TemperatureSensorsInstalled](#temperaturesensorsinstalled) 🔍 → `Boolean`
    - [UniChar](#unichar) 🔍 → `Text`
    - [WorksOrder](#worksorder) 🔍 → `Integer`
    - [WorksOrderEntity](#worksorderentity) 🔍 → `cs.WorksOrderEntity`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### checkTempZoneExists {#checktempzoneexists}


```4d
Function checkTempZoneExists($Zone : Integer) -> Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Zone` | `Integer` | - | - |

**Returns:** `Boolean`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### AssignedTemperatureSensorsPresent {#assignedtemperaturesensorspresent}
 `[🔍 get only]`

```4d
Function get AssignedTemperatureSensorsPresent -> Boolean
```

**Returns:** `Boolean`

---

#### Changing {#changing}
 `[🔍 get only]`

```4d
Function get Changing -> Boolean
```

**Returns:** `Boolean`

---

#### TemperatureSensorsInstalled {#temperaturesensorsinstalled}
 `[🔍 get only]`

```4d
Function get TemperatureSensorsInstalled -> Boolean
```

**Returns:** `Boolean`

---

#### UniChar {#unichar}
 `[🔍 get only]`

```4d
Function get UniChar -> Text
```

**Returns:** `Text`

---

#### WorksOrder {#worksorder}
 `[🔍 get only]`

```4d
Function get WorksOrder -> Integer
```

**Returns:** `Integer`

---

#### WorksOrderEntity {#worksorderentity}
 `[🔍 get only]`

```4d
Function get WorksOrderEntity -> cs.WorksOrderEntity
```

**Returns:** `cs.WorksOrderEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RealTimeMachines](../Tables/RealTimeMachines.md) - ORDA Entity class for RealTimeMachines table

### � Related Classes

- [RealTimeMachines](RealTimeMachines.md) - ORDA DataClass class for RealTimeMachines table

### � Forms

- [CurrentDownTime](../Forms/CurrentDownTime.md) - Data source for CurrentDownTime form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [MachineMaintenance](../Forms/MachineMaintenance.md) - Data source for MachineMaintenance form
- [RealTimeMonitor](../Forms/RealTimeMonitor.md) - Data source for RealTimeMonitor form
- [RealTimeViewer](../Forms/RealTimeViewer.md) - Data source for RealTimeViewer form
- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form

---

*Generated from RealTimeMachinesEntity.4dm*
