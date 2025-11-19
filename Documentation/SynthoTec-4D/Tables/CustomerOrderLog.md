---
layout : default
title : CustomerOrderLog
parent : Tables
---
# CustomerOrderLog

📊 **Overview:** 9 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 77
- **UUID:** 8921E64C9227D341A45DA81DDEBEFC8F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:55Z

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
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PetesNo | `Date` | 🚫 Not Null | - |
| OurDelivery | `Integer` | 🚫 Not Null | - |
| CustomerDelivery | `Integer` | 🚫 Not Null | - |
| QtyOrdered | `Date` | 🚫 Not Null | - |
| QtyDelivered | `Date` | 🚫 Not Null | - |
| PartPrice | `Boolean` | 🚫 Not Null | - |
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
*Generated at: 2025-11-13T23:18:55Z*
