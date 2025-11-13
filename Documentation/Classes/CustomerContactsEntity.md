---
layout : default
title : CustomerContactsEntity
parent : Classes
---
# CustomerContactsEntity

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T21:44:50.357Z*

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
Function getMigrationRules($RemoteEntity : cs.CustomerContactsEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.CustomerContactsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.CustomerContactsEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.CustomerContactsEntity` | - | - |

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

- [CustomerContacts](../Tables/CustomerContacts.md) - Source table for this ORDA class
- [CustomerContacts](../Tables/CustomerContacts.md) - Database table storing CustomerContacts records

### � Related Classes

- [CustomerContacts](CustomerContacts.md) - ORDA DataClass class for CustomerContacts table
- [CustomerContactsEntity](CustomerContactsEntity.md) - ORDA Entity class for CustomerContacts table

---

*Generated from CustomerContactsEntity.4dm*
