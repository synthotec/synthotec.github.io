---
layout : default
title : MaterialEntity
parent : Classes
---
# MaterialEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MaterialEntity.4dm)

📊 **Overview:** 3 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:07:28.226Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [getMaterialsUsingThis](#getmaterialsusingthis) → `cs.MaterialSelection`
  - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
  - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - [HasMigrationID](#hasmigrationid) → `Boolean`
- [🔗 Related Items](#related-items)
---

## Functions {#functions}

### Regular Functions

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

- [Material](../Tables/Material.md) - Source table for this ORDA class

### � Related Classes

- [Material](Material.md) - ORDA DataClass class for Material table

---

*Generated from MaterialEntity.4dm*
