---
layout : default
title : PackagingCatsEntity
parent : Classes
---
# PackagingCatsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PackagingCatsEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a packaging category (e.g., box, bag, pallet wrap) used when recording packaging consumption. Supports migration synchronisation from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.145Z*

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
Function getMigrationRules($RemoteEntity : cs.PackagingCatsEntity) -> $Collection : Collection
```

Returns collection of EntityMigrationRule objects defining how to merge packaging category with remote during sync

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.PackagingCatsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.PackagingCatsEntity)
```

Synchronizes related Supplies selection after packaging category entity merge

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.PackagingCatsEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [PackagingCats](../Tables/PackagingCats.md) - ORDA Entity class for PackagingCats table

### � Related Classes

- [PackagingCats](PackagingCats.md) - ORDA DataClass class for PackagingCats table

### � Forms

- [PC_List](../Forms/PC_List.md) - Data source for PC_List form
- [SupplyInfo](../Forms/SupplyInfo.md) - Data source for SupplyInfo form

---

*Generated from PackagingCatsEntity.4dm*
