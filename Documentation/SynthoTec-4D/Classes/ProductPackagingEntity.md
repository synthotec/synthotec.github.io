---
layout : default
title : ProductPackagingEntity
parent : Classes
---
# ProductPackagingEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductPackagingEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T18:12:03.525Z*

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
Function getMigrationRules($RemoteEntity : cs.ProductPackagingEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductPackagingEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ProductPackagingEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductPackagingEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [ProductPackaging](../Tables/ProductPackaging.md) - ORDA Entity class for ProductPackaging table

### � Related Classes

- [ProductPackaging](ProductPackaging.md) - ORDA DataClass class for ProductPackaging table

### � Forms

- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [TransferSupply](../Forms/TransferSupply.md) - Data source for TransferSupply form

---

*Generated from ProductPackagingEntity.4dm*
