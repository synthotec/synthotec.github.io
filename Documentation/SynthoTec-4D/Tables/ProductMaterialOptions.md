---
layout : default
title : ProductMaterialOptions
parent : Tables
---
# ProductMaterialOptions

📊 **Overview:** 6 Fields | 3 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 40
- **UUID:** 35B5E95C0975EB4583DCBCAD2723FA54
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:51Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| MaterialID | `Long Integer` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| CreatedDate | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ProductID` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ProductMaterialOptions](../Classes/ProductMaterialOptions.md) - ORDA DataClass class for ProductMaterialOptions table
- [ProductMaterialOptionsEntity](../Classes/ProductMaterialOptionsEntity.md) - ORDA Entity class for ProductMaterialOptions table

### 📄 Forms

- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:51Z*
