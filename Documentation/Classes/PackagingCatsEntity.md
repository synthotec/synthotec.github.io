---
layout : default
title : PackagingCatsEntity
parent : Classes
---
# PackagingCatsEntity

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T12:58:34.092Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (2):**

- [getMigrationRules](#getmigrationrules) (1 param) → `Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.PackagingCatsEntity) -> Collection
```

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

var $EntityMigration:=cs.EntityMigration.new(ds.Supplies; $RemoteEntity.SuppliesSelection)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.PackagingCatsEntity` | - | - |

---

## 🔗 Related Items

### 🗂️ Used By Tables

- [PackagingCats](../Tables/PackagingCats.md) - Entity class

---

*Generated from PackagingCatsEntity.4dm*
