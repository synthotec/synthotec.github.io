---
layout : default
title : GrippersEntity
parent : Classes
---
# GrippersEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/GrippersEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a gripper tooling component, storing part number, machine number, head number, gripper details, and cleaning instructions. Includes machine number conversion from S1 to S2 numbering during migration.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.877Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.GrippersEntity) -> $Collection : Collection
```

Define migration rules for syncing gripper data from remote entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.GrippersEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.GrippersEntity)
```

Synchronize related entity selections during migration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.GrippersEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [Grippers](../Tables/Grippers.md) - ORDA Entity class for Grippers table

### � Related Classes

- [Grippers](Grippers.md) - ORDA DataClass class for Grippers table

### � Forms

- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from GrippersEntity.4dm*
