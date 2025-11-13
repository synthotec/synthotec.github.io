---
layout : default
title : Location
parent : Tables
---
# Location

📊 **Overview:** 3 Fields | 2 Indexes | 1 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 121
- **UUID:** 44FBB6DE7626F84EA6B3129DC5AAA82E
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Name | `String` (255) | - | - |
| ParentLocationID | `String` | - | - |
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ParentLocationID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `LocationEntity` | [Location](Location.md) | `ParentLocationID` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PalletSelection` | [Pallet](Pallet.md) | `LocationID` → `ID` | Active | - |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `LocationID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Location](../Classes/Location.md) - DataClass class
- [LocationEntity](../Classes/LocationEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:45Z*
