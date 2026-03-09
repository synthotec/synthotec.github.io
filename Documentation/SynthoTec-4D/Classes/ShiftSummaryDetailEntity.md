---
layout : default
title : ShiftSummaryDetailEntity
parent : Classes
---
# ShiftSummaryDetailEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ShiftSummaryDetailEntity.4dm)

📊 **Overview:** 2 Functions | 3 Getters

## 📝 Description

Entity representing a detail line in a shift summary, linking a works order to a shift. Provides a method to calculate downtime since the previous shift by analysing production, planned downtime, and actual downtime periods in the interval.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:31.583Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [fillDowntimeSincePrevious](#filldowntimesinceprevious) 🖥️
    - [fillRealTimeOutputMachine](#fillrealtimeoutputmachine) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Status](#status) 🔍 → `Integer`
    - [StatusColor](#statuscolor) 🔍 → `Integer`
    - [StatusText](#statustext) 🔍 → `Text`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### fillDowntimeSincePrevious {#filldowntimesinceprevious}
 `[🖥️ local]`

```4d
Function fillDowntimeSincePrevious
```

Calculates downtime since previous shift by accounting for production, planned downtime, and current downtime periods

---

#### fillRealTimeOutputMachine {#fillrealtimeoutputmachine}
 `[🖥️ local]`

```4d
Function fillRealTimeOutputMachine($RealTimeMachinesEntity : cs.RealTimeMachinesEntity)
```

Populates RealTimeOutputMachine object from the given machine entity, excluding entity and selection references

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RealTimeMachinesEntity` | `cs.RealTimeMachinesEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Status {#status}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Status -> Integer
```

Returns status code based on works order dates (1=Finished, 2=Tool Change, 3=In Progress)

**Returns:** `Integer`

---

#### StatusColor {#statuscolor}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StatusColor -> Integer
```

Returns color indicating shift status (amber=Finished, light blue=Tool Change, green=In Progress)

**Returns:** `Integer`

---

#### StatusText {#statustext}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StatusText -> Text
```

Returns human-readable status text based on works order progress ("Finished", "Tool Change", or "")

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ShiftSummaryDetail](../Tables/ShiftSummaryDetail.md) - ORDA Entity class for ShiftSummaryDetail table

### � Forms

- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form

---

*Generated from ShiftSummaryDetailEntity.4dm*
