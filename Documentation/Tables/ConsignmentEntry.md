---
layout : default
title : ConsignmentEntry
parent : Tables
---
# ConsignmentEntry

📊 **Overview:** 27 Fields | 1 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 58
- **UUID:** 1D7F0D4EFE7DFD438D22AF0D3E4F1FCA
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:48:31Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (27)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StartDate | `Integer` | 🚫 Not Null | - |
| CustomerCode | `String` (255) | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| Week1 | `Date` | 🚫 Not Null | - |
| Week2 | `Date` | 🚫 Not Null | - |
| Week3 | `Date` | 🚫 Not Null | - |
| Week4 | `Date` | 🚫 Not Null | - |
| Week5 | `Date` | 🚫 Not Null | - |
| Week6 | `Date` | 🚫 Not Null | - |
| Week7 | `Date` | 🚫 Not Null | - |
| Week8 | `Date` | 🚫 Not Null | - |
| Week9 | `Date` | 🚫 Not Null | - |
| Week10 | `Date` | 🚫 Not Null | - |
| Week11 | `Date` | 🚫 Not Null | - |
| Week12 | `Date` | 🚫 Not Null | - |
| Archived | `Real` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| CustomerRef | `String` (255) | 🚫 Not Null | - |
| Week13 | `Date` | 🚫 Not Null | - |
| Week14 | `Date` | 🚫 Not Null | - |
| Week15 | `Date` | 🚫 Not Null | - |
| Week16 | `Date` | 🚫 Not Null | - |
| Week17 | `Date` | 🚫 Not Null | - |
| Week18 | `Date` | 🚫 Not Null | - |
| Week19 | `Date` | 🚫 Not Null | - |
| Week20 | `Date` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:31Z*
