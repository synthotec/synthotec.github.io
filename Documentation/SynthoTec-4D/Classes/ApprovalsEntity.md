---
layout : default
title : ApprovalsEntity
parent : Classes
---
# ApprovalsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ApprovalsEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a customer-tool approval record, storing approval type, conditional dates, bypass flags, and approver details. Supports data migration and synchronisation from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:28.992Z*

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
Function getMigrationRules($RemoteEntity : cs.ApprovalsEntity) -> $Collection : Collection
```

Defines migration rules for syncing approval entity data from a remote source

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ApprovalsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ApprovalsEntity)
```

Synchronizes related entity selections during migration process

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ApprovalsEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [Approvals](../Tables/Approvals.md) - ORDA Entity class for Approvals table

### � Related Classes

- [Approvals](Approvals.md) - ORDA DataClass class for Approvals table

---

*Generated from ApprovalsEntity.4dm*
