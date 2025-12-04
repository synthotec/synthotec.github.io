---
layout : default
title : ConsignmentEntry
parent : Tables
---
# ConsignmentEntry

📊 **Overview:** 27 Fields | 1 Indexes | 1 Many-to-One Relations

## 📝 Description

🗨️ Transaction table recording consignment stock movements into customer locations. Tracks products sent to customer sites but still owned by company.

## ℹ️ Table Information

- **Table ID:** 58
- **UUID:** 1D7F0D4EFE7DFD438D22AF0D3E4F1FCA
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:20Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (27)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StartDate | `Date` | 🚫 Not Null | - |
| CustomerCode | `String` (255) | 🚫 Not Null | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| Week1 | `Long Integer` | 🚫 Not Null | - |
| Week2 | `Long Integer` | 🚫 Not Null | - |
| Week3 | `Long Integer` | 🚫 Not Null | - |
| Week4 | `Long Integer` | 🚫 Not Null | - |
| Week5 | `Long Integer` | 🚫 Not Null | - |
| Week6 | `Long Integer` | 🚫 Not Null | - |
| Week7 | `Long Integer` | 🚫 Not Null | - |
| Week8 | `Long Integer` | 🚫 Not Null | - |
| Week9 | `Long Integer` | 🚫 Not Null | - |
| Week10 | `Long Integer` | 🚫 Not Null | - |
| Week11 | `Long Integer` | 🚫 Not Null | - |
| Week12 | `Long Integer` | 🚫 Not Null | - |
| Archived | `Boolean` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| CustomerRef | `String` (255) | 🚫 Not Null | - |
| Week13 | `Long Integer` | 🚫 Not Null | - |
| Week14 | `Long Integer` | 🚫 Not Null | - |
| Week15 | `Long Integer` | 🚫 Not Null | - |
| Week16 | `Long Integer` | 🚫 Not Null | - |
| Week17 | `Long Integer` | 🚫 Not Null | - |
| Week18 | `Long Integer` | 🚫 Not Null | - |
| Week19 | `Long Integer` | 🚫 Not Null | - |
| Week20 | `Long Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:20Z*
