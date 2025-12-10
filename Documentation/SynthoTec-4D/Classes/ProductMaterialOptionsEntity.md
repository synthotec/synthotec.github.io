---
layout : default
title : ProductMaterialOptionsEntity
parent : Classes
---
# ProductMaterialOptionsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductMaterialOptionsEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-12-10T11:45:23.979Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Default](#default) 🔍 → `Boolean`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ProductMaterialOptionsEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductMaterialOptionsEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ProductMaterialOptionsEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductMaterialOptionsEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Default {#default}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Default -> Boolean
```

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ProductMaterialOptions](../Tables/ProductMaterialOptions.md) - ORDA Entity class for ProductMaterialOptions table

### � Related Classes

- [ProductMaterialOptions](ProductMaterialOptions.md) - ORDA DataClass class for ProductMaterialOptions table

### � Forms

- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form

---

*Generated from ProductMaterialOptionsEntity.4dm*
