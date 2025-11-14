---
layout : default
title : PlanningWheel
parent : Classes
---
# PlanningWheel [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PlanningWheel.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T00:18:20.924Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
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

### � Related Classes

- [PlanningWheelEntity](PlanningWheelEntity.md) - ORDA Entity class for PlanningWheel table

---

*Generated from PlanningWheel.4dm*
