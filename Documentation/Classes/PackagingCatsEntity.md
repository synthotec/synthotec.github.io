---
layout : default
title : PackagingCatsEntity
parent : Classes
---
# PackagingCatsEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PackagingCatsEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T23:29:28.021Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.PackagingCatsEntity) -> $Collection : Collection
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

- [PackagingCats](../Tables/PackagingCats.md) - Source table for this ORDA class

### � Related Classes

- [PackagingCats](PackagingCats.md) - ORDA DataClass class for PackagingCats table

---

*Generated from PackagingCatsEntity.4dm*
