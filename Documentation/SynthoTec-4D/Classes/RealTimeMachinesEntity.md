---
layout : default
title : RealTimeMachinesEntity
parent : Classes
---
# RealTimeMachinesEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RealTimeMachinesEntity.4dm)

📊 **Overview:** 1 Functions | 6 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:13.102Z*

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

Returns true if the specified temperature zone is configured on this machine

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

Returns true if all assigned temperature sensors are present in the last cycle sensor data

**Returns:** `Boolean`

---

#### Changing {#changing}
 `[🔍 get only]`

```4d
Function get Changing -> Boolean
```

Returns true if machine is idle/changing (no active works order)

**Returns:** `Boolean`

---

#### TemperatureSensorsInstalled {#temperaturesensorsinstalled}
 `[🔍 get only]`

```4d
Function get TemperatureSensorsInstalled -> Boolean
```

Returns true if temperature sensors are configured and have zones defined

**Returns:** `Boolean`

---

#### UniChar {#unichar}
 `[🔍 get only]`

```4d
Function get UniChar -> Text
```

Returns the emoji character for the currently running product, or empty string if idle

**Returns:** `Text`

---

#### WorksOrder {#worksorder}
 `[🔍 get only]`

```4d
Function get WorksOrder -> Integer
```

Returns the currently running works order number, or 0 if no active order

**Returns:** `Integer`

---

#### WorksOrderEntity {#worksorderentity}
 `[🔍 get only]`

```4d
Function get WorksOrderEntity -> cs.WorksOrderEntity
```

Returns the currently running works order entity for this machine, or null if idle or multiple active

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
