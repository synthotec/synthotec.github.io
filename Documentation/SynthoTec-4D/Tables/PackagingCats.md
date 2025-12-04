---
layout : default
title : PackagingCats
parent : Tables
---
# PackagingCats

📊 **Overview:** 3 Fields | 1 Indexes | 1 One-to-Many Relations

## 📝 Description

🗨️ Lookup table defining packaging material categories (boxes, pallets, wrapping, labels). Referenced by ProductPackaging.

## ℹ️ Table Information

- **Table ID:** 36
- **UUID:** 0EB107798546B546BF08F545905BAA5F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:02Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Name | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `SuppliesSelection` | [Supplies](Supplies.md) | `PackagingCat` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [PackagingCats](../Classes/PackagingCats.md) - ORDA DataClass class for PackagingCats table
- [PackagingCatsEntity](../Classes/PackagingCatsEntity.md) - ORDA Entity class for PackagingCats table

### 📄 Forms

- [PC_List](../Forms/PC_List.md) - Data source for PC_List form
- [SupplyInfo](../Forms/SupplyInfo.md) - Data source for SupplyInfo form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:02Z*
