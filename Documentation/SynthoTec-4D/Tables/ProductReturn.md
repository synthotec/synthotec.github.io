---
layout : default
title : ProductReturn
parent : Tables
---
# ProductReturn

📊 **Overview:** 9 Fields | 3 Indexes | 1 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 30
- **UUID:** 84D5CEC865744441A28B55BDFF4F334A
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:10Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ReturnID_l | `Date` | 🚫 Not Null | - |
| DateOfReturn_d | `Integer` | 🚫 Not Null | - |
| ReturnNotes_txt | `String` | 🚫 Not Null | - |
| PQI_No_s | `String` (15) | 🚫 Not Null | - |
| CustomerOrderDetails_s | `String` (50) | 🚫 Not Null | - |
| ProductID_l | `Date` | 🚫 Not Null | - |
| CustomerCode_s | `String` (3) | 🚫 Not Null | - |
| ReturnClosed_b | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |
| `ProductID_l` | Keywords | regular | - |
| `ReturnID_l` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ProductReturnWorksOrderSelection` | [ProductReturnWorksOrder](ProductReturnWorksOrder.md) | `ReturnID_l` → `ReturnID_l` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:10Z*
