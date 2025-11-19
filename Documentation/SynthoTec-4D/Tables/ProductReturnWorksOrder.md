---
layout : default
title : ProductReturnWorksOrder
parent : Tables
---
# ProductReturnWorksOrder

📊 **Overview:** 8 Fields | 3 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 31
- **UUID:** 130945D5E0DF0E4498FBB20449311F51
- **Primary Key:** 🔑 `WOReturnID_l`
- **Generated:** 🕐 2025-11-13T23:18:11Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **WOReturnID_l** | `Date` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| ReturnID_l | `Date` | 🚫 Not Null | - |
| Works_Order_No_l | `Date` | 🚫 Not Null | - |
| ReturnedQuantity_l | `Date` | 🚫 Not Null | - |
| Scrapped_b | `Real` | 🚫 Not Null | - |
| Restocked_b | `Real` | 🚫 Not Null | - |
| ScrappedQuantity_l | `Date` | 🚫 Not Null | - |
| RestockedQuantity_l | `Date` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ReturnID_l` | Keywords | regular | - |
| `WOReturnID_l` | Keywords | regular | ✨ Yes |
| `Works_Order_No_l` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductReturnEntity` | [ProductReturn](ProductReturn.md) | `ReturnID_l` → `ReturnID_l` | Active | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No_l` → `Works_Order_No` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ProductReturnWorksOrderEntity](../Classes/ProductReturnWorksOrderEntity.md) - ORDA Entity class for ProductReturnWorksOrder table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:11Z*
