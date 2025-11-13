---
layout : default
title : ShiftSummaryDetailEntity
parent : Classes
---
# ShiftSummaryDetailEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ShiftSummaryDetailEntity.4dm)

📊 **Overview:** 2 Functions | 3 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T23:49:47.498Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#️-functions)
  - [fillDowntimeSincePrevious](#filldowntimesinceprevious) 🖥️
  - [fillRealTimeOutputMachine](#fillrealtimeoutputmachine) (1 param) 🖥️
  - [Status](#status) → `Integer`
  - [StatusText](#statustext) → `Text`
  - [StatusColor](#statuscolor) → `Integer`
- [🔗 Related Items](#-related-items)
---

## ⚙️ Functions

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

#### Status {#status}
 `[🖥️ local, 🔍 getter]`

```4d
Function Status -> Integer
```

**Returns:** `Integer`

---

#### StatusText {#statustext}
 `[🖥️ local, 🔍 getter]`

```4d
Function StatusText -> Text
```

**Returns:** `Text`

---

#### StatusColor {#statuscolor}
 `[🖥️ local, 🔍 getter]`

```4d
Function StatusColor -> Integer
```

**Returns:** `Integer`

---

## 🔗 Related Items

### 🗂️ Tables

- [ShiftSummaryDetail](../Tables/ShiftSummaryDetail.md) - Source table for this ORDA class

---

*Generated from ShiftSummaryDetailEntity.4dm*
