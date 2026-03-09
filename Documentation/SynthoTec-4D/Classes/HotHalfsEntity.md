---
layout : default
title : HotHalfsEntity
parent : Classes
---
# HotHalfsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/HotHalfsEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a hot half component of an injection moulding tool, storing its name, count, and description. Supports migration synchronisation from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.888Z*

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
Function getMigrationRules($RemoteEntity : cs.HotHalfsEntity) -> $Collection : Collection
```

Define migration rules for syncing hot half data from remote entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.HotHalfsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.HotHalfsEntity)
```

Synchronize related entity selections during migration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.HotHalfsEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [HotHalfs](../Tables/HotHalfs.md) - ORDA Entity class for HotHalfs table

### � Related Classes

- [HotHalfs](HotHalfs.md) - ORDA DataClass class for HotHalfs table

### � Forms

- [HotHalfManager](../Forms/HotHalfManager.md) - Data source for HotHalfManager form
- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from HotHalfsEntity.4dm*
