---
layout : default
title : ProductPackagingEntity
parent : Classes
---
# ProductPackagingEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductPackagingEntity.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

Entity representing a packaging item assigned to a product (linking product, supplies, and quantity), with migration sync support that maps product and supplies IDs from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.861Z*

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

Returns migration rules for syncing this product packaging with remote entity (maps Product/Supplies IDs, overwrites Quantity)

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

Syncs migration selections for this product packaging with remote entity during data migration

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
