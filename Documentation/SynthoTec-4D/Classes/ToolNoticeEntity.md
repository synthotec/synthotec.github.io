---
layout : default
title : ToolNoticeEntity
parent : Classes
---
# ToolNoticeEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ToolNoticeEntity.4dm)

📊 **Overview:** 2 Functions | 3 Getters

## 📝 Description

Entity representing a tool notice or production hold, storing notice type, active flag, and remaining runs. The IsActive computed property respects both the active flag and the runs-based expiry (RunsActiveFor=-1 means unlimited runs).

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:31.751Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [displayWorkOrders](#displayworkorders) 🖥️
    - [deactivate](#deactivate) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [ActiveUntilText](#activeuntiltext) 🔍 → `Text`
    - [IsActive](#isactive) 🔍 → `Boolean`
    - [RemainingRuns](#remainingruns) 🔍 → `Integer`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### displayWorkOrders {#displayworkorders}
 `[🖥️ local]`

```4d
Function displayWorkOrders
```

Displays list of works orders started while this tool notice was active

---

#### deactivate {#deactivate}
 `[🖥️ local]`

```4d
Function deactivate
```

Deactivates this tool notice after permission check, locking, and user confirmation

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### ActiveUntilText {#activeuntiltext}
 `[🔍 get only]`

```4d
Function get ActiveUntilText -> Text
```

Returns formatted text showing when notice expires (manually deactivated, unlimited, or remaining tool changes)

**Returns:** `Text`

---

#### IsActive {#isactive}
 `[🔍 get only]`

```4d
Function get IsActive -> Boolean
```

Returns true if notice is active and has remaining runs (or unlimited runs with RunsActiveFor=-1)

**Returns:** `Boolean`

---

#### RemainingRuns {#remainingruns}
 `[🔍 get only]`

```4d
Function get RemainingRuns -> Integer
```

Returns number of remaining work orders before notice expires, 0 if unlimited (RunsActiveFor=-1)

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ToolNotice](../Tables/ToolNotice.md) - ORDA Entity class for ToolNotice table

### � Related Classes

- [ToolNotice](ToolNotice.md) - ORDA DataClass class for ToolNotice table

### � Forms

- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from ToolNoticeEntity.4dm*
