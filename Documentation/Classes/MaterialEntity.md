---
layout : default
title : MaterialEntity
parent : Classes
---
# MaterialEntity

📊 **Overview:** 3 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T16:46:52.088Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (3):**

- [getMaterialsUsingThis](#getmaterialsusingthis) → `cs.MaterialSelection`
- [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

**🔍 Getters (1):**

- [HasMigrationID](#hasmigrationid) → `Boolean`

### 🔗 Related Items

- [Tables](#️-tables) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getMaterialsUsingThis {#getmaterialsusingthis}


```4d
Function getMaterialsUsingThis -> cs.MaterialSelection
```

**Returns:** `cs.MaterialSelection`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.MaterialEntity) -> $Collection : Collection
```

////////////////////////////////////////////////////////////////////////////////////////

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.MaterialEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.MaterialEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.MaterialEntity` | - | - |

---

### 🔍 Getters

#### HasMigrationID {#hasmigrationid}
 `[🖥️ local, 🔍 getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

## 🔗 Related Items

### 🗂️ Tables

- [Material](../Tables/Material.md) - Source table

---

*Generated from MaterialEntity.4dm*
