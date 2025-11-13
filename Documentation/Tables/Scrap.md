---
layout : default
title : Scrap
parent : Tables
---
# Scrap

📊 **Overview:** 15 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 47
- **UUID:** B91E3A24E0704F41AAE38F93EE48B9E6
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:08:30Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (15)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| DateScrapped | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| DateProduced | `Integer` | 🚫 Not Null | - |
| Fault | `String` (255) | 🚫 Not Null | - |
| Reason | `String` (255) | 🚫 Not Null | - |
| Quantity | `Date` | 🚫 Not Null | - |
| Location | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| ScrappedBy | `String` (255) | 🚫 Not Null | - |
| New | `Real` | 🚫 Not Null | - |
| Shift | `Date` | 🚫 Not Null | - |
| Sequence | `Picture` | 🚫 Not Null | - |
| Comment | `String` (255) | 🚫 Not Null | - |
| DateTimeScrapped | `String` (255) | 🚫 Not Null | - |
| ShiftDate | `Date` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ShiftDate` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:30Z*
