---
layout : default
title : PlanningWheel
parent : Classes
---
# PlanningWheel [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PlanningWheel.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T23:29:28.259Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [insertLine](#insertline) (2 params) → `$PlanningWheelEntity : cs.PlanningWheelEntity` 🖥️
- [reducePlannedStand](#reduceplannedstand) 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

## 🔗 Related Items

### 🗂️ Tables

- [PlanningWheel](../Tables/PlanningWheel.md) - Source table for this ORDA class

### � Related Classes

- [PlanningWheelEntity](PlanningWheelEntity.md) - ORDA Entity class for PlanningWheel table

---

*Generated from PlanningWheel.4dm*
