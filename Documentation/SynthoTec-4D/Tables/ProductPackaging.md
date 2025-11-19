---
layout : default
title : ProductPackaging
parent : Tables
---
# ProductPackaging

📊 **Overview:** 9 Fields | 6 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 35
- **UUID:** A0DC125CC548024984CE4F807E2D45E2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:15Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ToolID | `Date` | 🚫 Not Null | - |
| SuppliesID | `Picture` | 🚫 Not Null | - |
| Quantity | `Boolean` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |
| Customer | `String` (255) | - | - |
| CustomerSpecific | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `CustomerSpecific` | Keywords | regular | - |
| `Customer` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `ToolID` | Keywords | regular | - |
| `ProductID` | Keywords | regular | - |
| `SuppliesID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `SuppliesEntity` | [Supplies](Supplies.md) | `SuppliesID` → `UniqueID_i` | Active | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ProductPackaging](../Classes/ProductPackaging.md) - ORDA DataClass class for ProductPackaging table
- [ProductPackagingEntity](../Classes/ProductPackagingEntity.md) - ORDA Entity class for ProductPackaging table

### 📄 Forms

- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [TransferSupply](../Forms/TransferSupply.md) - Data source for TransferSupply form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:15Z*
