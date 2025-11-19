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
- **Generated:** 🕐 2025-11-13T23:19:23Z

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
| MondayDespatch | `Real` | 🚫 Not Null | - |
| MondayDays | `Picture` | 🚫 Not Null | - |
| TuesdayDespatch | `Real` | 🚫 Not Null | - |
| TuesdayDays | `Picture` | 🚫 Not Null | - |
| WednesdayDespatch | `Real` | 🚫 Not Null | - |
| WednesdayDays | `Picture` | 🚫 Not Null | - |
| ThursdayDespatch | `Real` | 🚫 Not Null | - |
| ThursdayDays | `Picture` | 🚫 Not Null | - |
| FridayDespatch | `Real` | 🚫 Not Null | - |
| FridayDays | `Picture` | 🚫 Not Null | - |
| SaturdayDespatch | `Real` | 🚫 Not Null | - |
| SaturdayDays | `Picture` | 🚫 Not Null | - |
| SundayDespatch | `Real` | 🚫 Not Null | - |
| SundayDays | `Picture` | 🚫 Not Null | - |
| CustomerCode | `String` | 🚫 Not Null | - |
| AdminLeadTimeDays | `Picture` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:23Z*
