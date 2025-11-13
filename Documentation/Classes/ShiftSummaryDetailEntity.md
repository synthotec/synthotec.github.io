---
layout : default
title : ShiftSummaryDetailEntity
parent : Classes
---
# ShiftSummaryDetailEntity

📊 **Overview:** 2 Functions | 3 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T12:58:34.627Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (2):**

- [fillDowntimeSincePrevious](#filldowntimesinceprevious) 🖥️
- [fillRealTimeOutputMachine](#fillrealtimeoutputmachine) (1 param) 🖥️

**🔍 Getters (3):**

- [Status](#status) → `Integer`
- [StatusText](#statustext) → `Text`
- [StatusColor](#statuscolor) → `Integer`

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

### 🔍 Getters

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

### 🗂️ Used By Tables

- [ShiftSummaryDetail](../Tables/ShiftSummaryDetail.md) - Entity class

---

*Generated from ShiftSummaryDetailEntity.4dm*
