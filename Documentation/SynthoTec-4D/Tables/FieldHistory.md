---
layout : default
title : FieldHistory
parent : Tables
---
# FieldHistory

📊 **Overview:** 7 Fields | 5 Indexes

## ℹ️ Table Information

- **Table ID:** 102
- **UUID:** D4E78D9BFB953A4889052AAB5F6072AF
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:47Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (5)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (5)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Table | `Long Integer` | 🚫 Not Null | - |
| Field | `Long Integer` | 🚫 Not Null | - |
| PrimaryKey | `Long Integer` | 🚫 Not Null | - |
| ChangedBy | `String` (255) | 🚫 Not Null | - |
| ChangedDateTime | `String` (255) | 🚫 Not Null | - |
| Value | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `PrimaryKey` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Table` | B-Tree | regular | - |
| `Table` | Keywords | regular | - |
| `Field` | Keywords | regular | - |

## 🔗 Related Items

### 📦 Classes

- [FieldHistory](../Classes/FieldHistory.md) - ORDA DataClass class for FieldHistory table

### 📄 Forms

- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:47Z*
