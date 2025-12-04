---
layout : default
title : CustomerOrderLog
parent : Tables
---
# CustomerOrderLog

📊 **Overview:** 9 Fields | 2 Indexes

## 📝 Description

🗨️ Audit table logging changes to customer orders. Tracks modifications to quantities, dates, status, and other order details for traceability.

## ℹ️ Table Information

- **Table ID:** 77
- **UUID:** 8921E64C9227D341A45DA81DDEBEFC8F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:39Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PetesNo | `Long Integer` | 🚫 Not Null | - |
| OurDelivery | `Date` | 🚫 Not Null | - |
| CustomerDelivery | `Date` | 🚫 Not Null | - |
| QtyOrdered | `Long Integer` | 🚫 Not Null | - |
| QtyDelivered | `Long Integer` | 🚫 Not Null | - |
| PartPrice | `Real` | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| ModifiedBy | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `PetesNo` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:39Z*
