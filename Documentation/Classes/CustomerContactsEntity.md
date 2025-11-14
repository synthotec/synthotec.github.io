---
layout : default
title : CustomerContactsEntity
parent : Classes
---
# CustomerContactsEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CustomerContactsEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:02:21.810Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#️-functions)
  - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
  - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - [HasMigrationID](#hasmigrationid) → `Boolean`
- [🔗 Related Items](#related-items)
---

## ⚙️ Functions

### Regular Functions

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

### Getters

#### HasMigrationID {#hasmigrationid}
 `[🖥️ local, 🔍 getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [CustomerContacts](../Tables/CustomerContacts.md) - Source table for this ORDA class

### � Related Classes

- [CustomerContacts](CustomerContacts.md) - ORDA DataClass class for CustomerContacts table

---

*Generated from CustomerContactsEntity.4dm*
