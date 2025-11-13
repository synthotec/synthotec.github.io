---
layout : default
title : PackagingCatsEntity
parent : Classes
---
# PackagingCatsEntity

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T13:39:36.011Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [getMigrationRules](#getmigrationrules) (1 param) → `Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

### 🔗 Related Items

- [Tables](#-tables) (1)

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

### 🗂️ Tables

- [PackagingCats](../Tables/PackagingCats.md) - Entity class

---

*Generated from PackagingCatsEntity.4dm*
