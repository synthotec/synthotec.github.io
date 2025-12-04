---
layout : default
title : Gauges
parent : Tables
---
# Gauges

📊 **Overview:** 8 Fields | 2 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 23
- **UUID:** B84C6CC0E8E67246A59E39321DB56B95
- **Primary Key:** 🔑 `Unique_ID`
- **Generated:** 🕐 2025-12-03T16:23:36Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Unique_ID** | `Integer` | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Product_ID | `Long Integer` | ⚠️ Required, 🚫 Not Null | - |
| Type | `String` (40) | 🚫 Not Null | - |
| DateLastChecked | `Date` | 🚫 Not Null | - |
| LastCheckedbyWhom | `String` (50) | 🚫 Not Null | - |
| No_BetweenChecks | `Integer` | 🚫 Not Null | - |
| NoOfDaysUsage | `Integer` | 🚫 Not Null | - |
| NoOfDaysUsageLeft | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Product_ID` | Keywords | regular | - |
| `Unique_ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `Product_ID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [GaugesEntity](../Classes/GaugesEntity.md) - ORDA Entity class for Gauges table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:36Z*
