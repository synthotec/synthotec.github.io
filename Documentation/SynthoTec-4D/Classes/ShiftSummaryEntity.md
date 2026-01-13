---
layout : default
title : ShiftSummaryEntity
parent : Classes
---
# ShiftSummaryEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ShiftSummaryEntity.4dm)

📊 **Overview:** 1 Functions | 2 Getters

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:13.393Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getPreviousShiftSummaryEntity](#getpreviousshiftsummaryentity) → `cs.ShiftSummaryEntity` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [ShiftColor](#shiftcolor) 🔍 → `Integer`
    - [ShiftSymbol](#shiftsymbol) 🔍 → `Text`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getPreviousShiftSummaryEntity {#getpreviousshiftsummaryentity}
 `[🖥️ local]`

```4d
Function getPreviousShiftSummaryEntity -> cs.ShiftSummaryEntity
```

Returns the previous shift summary (closest one by ID) before this shift

**Returns:** `cs.ShiftSummaryEntity`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### ShiftColor {#shiftcolor}
 `[🔍 get only, 🖥️ local]`

```4d
Function get ShiftColor -> Integer
```

Returns color representing shift time (dark gray=night, golden yellow=morning, light sky blue=afternoon)

**Returns:** `Integer`

---

#### ShiftSymbol {#shiftsymbol}
 `[🔍 get only, 🖥️ local]`

```4d
Function get ShiftSymbol -> Text
```

Returns emoji symbol representing shift time (🌙 night, 🐓 morning, ☀️ afternoon)

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ShiftSummary](../Tables/ShiftSummary.md) - ORDA Entity class for ShiftSummary table

### � Forms

- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form

---

*Generated from ShiftSummaryEntity.4dm*
