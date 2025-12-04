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
- **Generated:** 🕐 2025-12-03T16:23:30Z

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
| CustomerDeliveryDate | `Date` | 🚫 Not Null | - |
| OurDeliveryDate | `Date` | 🚫 Not Null | - |
| QuantityOrdered | `Long Integer` | 🚫 Not Null | - |
| Nominal Sale | `Real` | 🚫 Not Null | - |
| Is_Replacement | `Boolean` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:30Z*
