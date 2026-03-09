---
layout : default
title : PackingInstructionFilesEntity
parent : Classes
---
# PackingInstructionFilesEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PackingInstructionFilesEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a versioned packing instruction document stored as a BLOB, including file name, upload timestamp, uploaded-by staff, version number, and the linked product entity. Supports migration sync from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.156Z*

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
Function getMigrationRules($RemoteEntity : cs.PackingInstructionFilesEntity) -> $Collection : Collection
```

Returns migration rules for syncing packing instruction files during data migration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.PackingInstructionFilesEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.PackingInstructionFilesEntity)
```

Syncs related entity selections during data migration for packing instructions (currently empty)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.PackingInstructionFilesEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [PackingInstructionFiles](../Tables/PackingInstructionFiles.md) - ORDA Entity class for PackingInstructionFiles table

### � Related Classes

- [PackingInstructionFiles](PackingInstructionFiles.md) - ORDA DataClass class for PackingInstructionFiles table

### � Forms

- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form

---

*Generated from PackingInstructionFilesEntity.4dm*
