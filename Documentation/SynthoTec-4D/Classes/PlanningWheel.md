---
layout : default
title : PlanningWheel
parent : Classes
---
# PlanningWheel [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PlanningWheel.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-19T15:47:09.142Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [insertLine](#insertline) (2 params) → `$PlanningWheelEntity : cs.PlanningWheelEntity` 🖥️
    - [reducePlannedStand](#reduceplannedstand) 🖥️
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### insertLine {#insertline}
 `[🖥️ local]`

```4d
Function insertLine($Machine : Integer; $RunOrder : Integer) -> $PlanningWheelEntity : cs.PlanningWheelEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Machine` | `Integer` | - | - |
| `$RunOrder` | `Integer` | - | - |

**Returns:** `cs.PlanningWheelEntity`

---

#### reducePlannedStand {#reduceplannedstand}
 `[🖥️ local]`

```4d
Function reducePlannedStand
```

---

## Related Items {#related-items}

### 🗂️ Tables

- [PlanningWheel](../Tables/PlanningWheel.md) - Source table for this ORDA class

---

*Generated from PlanningWheel.4dm*
