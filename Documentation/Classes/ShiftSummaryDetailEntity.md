---
layout : default
title : ShiftSummaryDetailEntity
parent : Classes
---
# ShiftSummaryDetailEntity

📊 **Overview:** 2 Functions | 3 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T21:44:55.319Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [fillDowntimeSincePrevious](#filldowntimesinceprevious) 🖥️
- [fillRealTimeOutputMachine](#fillrealtimeoutputmachine) (1 param) 🖥️

**🔍 Getters (3):**

- [Status](#status) → `Integer`
- [StatusText](#statustext) → `Text`
- [StatusColor](#statuscolor) → `Integer`

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (1)

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

### 🗂️ Tables

- [ShiftSummaryDetail](../Tables/ShiftSummaryDetail.md) - Source table for this ORDA class
- [ShiftSummaryDetail](../Tables/ShiftSummaryDetail.md) - Database table storing ShiftSummaryDetail records

### � Related Classes

- [ShiftSummaryDetailEntity](ShiftSummaryDetailEntity.md) - ORDA Entity class for ShiftSummaryDetail table

---

*Generated from ShiftSummaryDetailEntity.4dm*
