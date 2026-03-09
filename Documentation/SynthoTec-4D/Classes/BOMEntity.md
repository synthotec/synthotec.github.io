---
layout : default
title : BOMEntity
parent : Classes
---
# BOMEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/BOMEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a Bill of Materials record, storing part weights, runner weights, regrind, waste factors, material values, sales prices, and energy costs. Supports migration synchronisation from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.006Z*

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
Function getMigrationRules($RemoteEntity : cs.BOMEntity) -> $Collection : Collection
```

Defines migration rules for syncing Bill of Materials entity data from a remote source

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.BOMEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.BOMEntity)
```

Synchronizes related entity selections during migration process

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.BOMEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [BOM](../Tables/BOM.md) - ORDA Entity class for BOM table

### � Related Classes

- [BOM](BOM.md) - ORDA DataClass class for BOM table

### � Forms

- [BOM](../Forms/BOM.md) - Data source for BOM form
- [BOM_Output](../Forms/BOM_Output.md) - Data source for BOM_Output form

---

*Generated from BOMEntity.4dm*
