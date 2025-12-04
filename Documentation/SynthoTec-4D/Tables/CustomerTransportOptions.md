---
layout : default
title : CustomerTransportOptions
parent : Tables
---
# CustomerTransportOptions

📊 **Overview:** 18 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 106
- **UUID:** C94DE605E684BF448B7ED866B02B6D37
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:50Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| TransportOption | `String` (255) | 🚫 Not Null | - |
| MondayDespatch | `Boolean` | 🚫 Not Null | - |
| MondayDays | `Integer` | 🚫 Not Null | - |
| TuesdayDespatch | `Boolean` | 🚫 Not Null | - |
| TuesdayDays | `Integer` | 🚫 Not Null | - |
| WednesdayDespatch | `Boolean` | 🚫 Not Null | - |
| WednesdayDays | `Integer` | 🚫 Not Null | - |
| ThursdayDespatch | `Boolean` | 🚫 Not Null | - |
| ThursdayDays | `Integer` | 🚫 Not Null | - |
| FridayDespatch | `Boolean` | 🚫 Not Null | - |
| FridayDays | `Integer` | 🚫 Not Null | - |
| SaturdayDespatch | `Boolean` | 🚫 Not Null | - |
| SaturdayDays | `Integer` | 🚫 Not Null | - |
| SundayDespatch | `Boolean` | 🚫 Not Null | - |
| SundayDays | `Integer` | 🚫 Not Null | - |
| CustomerCode | `String` | 🚫 Not Null | - |
| AdminLeadTimeDays | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:50Z*
