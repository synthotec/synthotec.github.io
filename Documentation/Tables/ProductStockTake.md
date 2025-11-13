---
layout : default
title : ProductStockTake
parent : Tables
---
# ProductStockTake

📊 **Overview:** 7 Fields | 1 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 55
- **UUID:** CD7EC16B6973004E85CD5D29E07127D6
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:08:38Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| WO | `Date` | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| PartsCounted | `Date` | 🚫 Not Null | - |
| BoxesCounted | `Picture` | 🚫 Not Null | - |
| ActualStock | `Date` | 🚫 Not Null | - |
| sDate | `Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WO` → `Works_Order_No` | Active | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:38Z*
