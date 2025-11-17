---
layout : default
title : Customer_Order_Entry
parent : Tables
---
# Customer_Order_Entry

📊 **Overview:** 8 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 16
- **UUID:** AF0EF9F5DE55394BA5A574DC03975466
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:17:55Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Order_ID | `String` (10) | 🚫 Not Null | - |
| Batch_No | `String` (3) | 🚫 Not Null | - |
| CustomerDeliveryDate | `Integer` | 🚫 Not Null | - |
| OurDeliveryDate | `Integer` | 🚫 Not Null | - |
| QuantityOrdered | `Date` | 🚫 Not Null | - |
| Nominal Sale | `Boolean` | 🚫 Not Null | - |
| Is_Replacement | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:55Z*
