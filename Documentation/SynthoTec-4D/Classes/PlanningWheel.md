---
layout : default
title : PlanningWheel
parent : Classes
---
# PlanningWheel [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PlanningWheel.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

DataClass for the production planning wheel (schedule), providing UI-based line insertion that prompts for tool selection and quantity, then creates a new schedule entry and updates surrounding run orders.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.554Z*

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

Prompts user to select tool and quantity, creates planning wheel line and updates run orders

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

Reduces planned stand times by actual production runs and removes completed planning entries

---

## Related Items {#related-items}

### 🗂️ Tables

- [PlanningWheel](../Tables/PlanningWheel.md) - ORDA DataClass class for PlanningWheel table

### � Related Classes

- [PlanningWheelEntity](PlanningWheelEntity.md) - ORDA Entity class for PlanningWheel table

### � Forms

- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form

---

*Generated from PlanningWheel.4dm*
