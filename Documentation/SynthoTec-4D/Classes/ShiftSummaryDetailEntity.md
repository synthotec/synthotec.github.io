---
layout : default
title : ShiftSummaryDetailEntity
parent : Classes
---
# ShiftSummaryDetailEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ShiftSummaryDetailEntity.4dm)

📊 **Overview:** 2 Functions | 3 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T15:47:09.843Z*

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

---

#### fillRealTimeOutputMachine {#fillrealtimeoutputmachine}
 `[🖥️ local]`

```4d
Function fillRealTimeOutputMachine($RealTimeMachinesEntity : cs.RealTimeMachinesEntity)
```

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

**Returns:** `Integer`

---

#### StatusColor {#statuscolor}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StatusColor -> Integer
```

**Returns:** `Integer`

---

#### StatusText {#statustext}
 `[🔍 get only, 🖥️ local]`

```4d
Function get StatusText -> Text
```

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ShiftSummaryDetail](../Tables/ShiftSummaryDetail.md) - Source table for this ORDA class

---

*Generated from ShiftSummaryDetailEntity.4dm*
