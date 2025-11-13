---
layout : default
title : Supplies
parent : Tables
---
# Supplies

📊 **Overview:** 19 Fields | 3 Indexes | 2 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 20
- **UUID:** B84FAAF4158D23479C7828325B99FDF5
- **Primary Key:** 🔑 `UniqueID_i`
- **Generated:** 🕐 2025-11-13T02:47:56Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (19)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **UniqueID_i** | `Picture` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | - |
| Name_s | `String` (31) | 🚫 Not Null | - |
| Ref_s | `String` (20) | 🚫 Not Null | - |
| Description_txt | `String` | 🚫 Not Null | - |
| Price_r | `Boolean` | 🚫 Not Null | - |
| PriceQuantity_l | `Date` | 🚫 Not Null | - |
| MinOrderQty_r | `Boolean` | 🚫 Not Null | - |
| SupplierID_l | `Date` | 🚫 Not Null | - |
| UnitOfSale_s | `String` (20) | 🚫 Not Null | - |
| StockQty_r | `Boolean` | 🚫 Not Null | - |
| AdditionalInfo_txt | `String` | 🚫 Not Null | - |
| Currency_s | `String` (3) | 🚫 Not Null | - |
| IsPackaging | `Real` | 🚫 Not Null | - |
| PackagingCat | `Date` | 🚫 Not Null | - |
| RawMaterial | `Real` | 🚫 Not Null | - |
| MaterialID | `Date` | 🚫 Not Null | - |
| ReuseTimes | `Picture` | 🚫 Not Null | - |
| MarginDeduction | `Real` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `UniqueID_i` | Keywords | regular | ✨ Yes |
| `MaterialID` | Keywords | regular | - |
| `SupplierID_l` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `SuppliersEntity` | [Suppliers](Suppliers.md) | `SupplierID_l` → `SupplierID_l` | Active | - |
| `PackagingCatsEntity` | [PackagingCats](PackagingCats.md) | `PackagingCat` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `SuppliesID` → `UniqueID_i` | Active | - |
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `SuppliesID_i` → `UniqueID_i` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Supplies](../Classes/Supplies.md) - DataClass class
- [SuppliesEntity](../Classes/SuppliesEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:47:56Z*
