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
- **Generated:** 🕐 2025-11-13T23:18:03Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Unique_ID** | `Picture` | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| Product_ID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Type | `String` (40) | 🚫 Not Null | - |
| DateLastChecked | `Integer` | 🚫 Not Null | - |
| LastCheckedbyWhom | `String` (50) | 🚫 Not Null | - |
| No_BetweenChecks | `Picture` | 🚫 Not Null | - |
| NoOfDaysUsage | `Picture` | 🚫 Not Null | - |
| NoOfDaysUsageLeft | `Picture` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Product_ID` | Keywords | regular | - |
| `Unique_ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `Product_ID` → `Product_ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:03Z*
