---
layout : default
title : ProductMaterialOptions
parent : Classes
---
# ProductMaterialOptions [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductMaterialOptions.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for product material option records, defining which materials can be used to produce each product. Supports entity migration (linking disabled).

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.840Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns migration configuration disabling entity linking for ProductMaterialOptions

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [ProductMaterialOptions](../Tables/ProductMaterialOptions.md) - ORDA DataClass class for ProductMaterialOptions table

### � Related Classes

- [ProductMaterialOptionsEntity](ProductMaterialOptionsEntity.md) - ORDA Entity class for ProductMaterialOptions table

### � Forms

- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form

---

*Generated from ProductMaterialOptions.4dm*
