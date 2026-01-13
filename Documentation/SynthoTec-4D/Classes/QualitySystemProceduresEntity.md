---
layout : default
title : QualitySystemProceduresEntity
parent : Classes
---
# QualitySystemProceduresEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/QualitySystemProceduresEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:13.035Z*

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
Function getMigrationRules($RemoteEntity : cs.QualitySystemProceduresEntity) -> $Collection : Collection
```

Returns migration rules for syncing this quality procedure with remote entity (fills System/Procedure, overwrites limits/order, maps Product)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.QualitySystemProceduresEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.QualitySystemProceduresEntity)
```

Syncs migration selections for this quality procedure with remote entity during data migration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.QualitySystemProceduresEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [QualitySystemProcedures](../Tables/QualitySystemProcedures.md) - ORDA Entity class for QualitySystemProcedures table

### � Related Classes

- [QualitySystemProcedures](QualitySystemProcedures.md) - ORDA DataClass class for QualitySystemProcedures table

### � Forms

- [QualitySystemProcedures](../Forms/QualitySystemProcedures.md) - Data source for QualitySystemProcedures form

---

*Generated from QualitySystemProceduresEntity.4dm*
