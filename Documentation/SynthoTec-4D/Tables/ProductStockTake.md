---
layout : default
title : ProductStockTake
parent : Tables
---
# ProductStockTake

📊 **Overview:** 7 Fields | 1 Indexes | 2 Many-to-One Relations

## 📝 Description

🗨️ Transaction table recording physical finished goods inventory counts. Used for periodic stocktakes to verify system quantities against physical stock.

## ℹ️ Table Information

- **Table ID:** 55
- **UUID:** CD7EC16B6973004E85CD5D29E07127D6
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:17Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| WO | `Long Integer` | 🚫 Not Null | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| PartsCounted | `Long Integer` | 🚫 Not Null | - |
| BoxesCounted | `Integer` | 🚫 Not Null | - |
| ActualStock | `Long Integer` | 🚫 Not Null | - |
| sDate | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WO` → `Works_Order_No` | Active | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [ProductStockTake](../Forms/ProductStockTake.md) - Data source for ProductStockTake form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:17Z*
