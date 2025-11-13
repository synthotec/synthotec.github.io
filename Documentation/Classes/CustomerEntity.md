---
layout : default
title : CustomerEntity
parent : Classes
---
# CustomerEntity

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T21:44:50.398Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️

**🔍 Getters (1):**

- [HasMigrationID](#hasmigrationid) → `Boolean`

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.CustomerEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.CustomerEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.CustomerEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.CustomerEntity` | - | - |

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

- [Customer](../Tables/Customer.md) - Source table for this ORDA class
- [Customer](../Tables/Customer.md) - Database table storing Customer records

### � Related Classes

- [Customer](Customer.md) - ORDA DataClass class for Customer table
- [CustomerEntity](CustomerEntity.md) - ORDA Entity class for Customer table

---

*Generated from CustomerEntity.4dm*
