---
layout : default
title : Finished_Stock
parent : Tables
---
# Finished_Stock

📊 **Overview:** 12 Fields | 6 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 12
- **UUID:** 51AABC1ABE247B49864812D98CE6E30B
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:08:01Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| FinishedStockID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| ProductID_l | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Reuse_Issue_No | `String` (5) | 🚫 Not Null | - |
| MaterialID | `Picture` | 🚫 Not Null | - |
| Stock_Quantity | `Date` | 🚫 Not Null | - |
| Reuse_NoOfBoxes | `Date` | 🚫 Not Null | - |
| Reuse_PartBoxQty | `Date` | 🚫 Not Null | - |
| Reuse_WIP | `Date` | 🚫 Not Null | - |
| LocationID_l | `Date` | 🚫 Not Null | - |
| Works_Order_No | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Pallet_ID | `Date` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `LocationID_l` | Keywords | regular | - |
| `ProductID_l` | Keywords | regular | - |
| `Works_Order_No` | Keywords | regular | - |
| `FinishedStockID` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | Active | - |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `LocationID_l` → `StockLocationID_l` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:01Z*
