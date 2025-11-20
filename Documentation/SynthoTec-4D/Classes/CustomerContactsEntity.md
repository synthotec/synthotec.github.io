---
layout : default
title : CustomerContactsEntity
parent : Classes
---
# CustomerContactsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CustomerContactsEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-20T14:23:48.729Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [HasMigrationID](#hasmigrationid) 🔍 → `Boolean`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.CustomerContactsEntity) -> $Collection : Collection
```

Defines migration rules for syncing customer contact entity data from a remote source

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

Synchronizes related entity selections during migration process

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.CustomerContactsEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

Returns true if this entity has a valid migration ID (not null and not zero)

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [CustomerContacts](../Tables/CustomerContacts.md) - ORDA Entity class for CustomerContacts table

### � Related Classes

- [CustomerContacts](CustomerContacts.md) - ORDA DataClass class for CustomerContacts table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form
- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form

---

*Generated from CustomerContactsEntity.4dm*
