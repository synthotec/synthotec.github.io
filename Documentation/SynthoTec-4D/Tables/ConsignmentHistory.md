---
layout : default
title : ConsignmentHistory
parent : Tables
---
# ConsignmentHistory

📊 **Overview:** 6 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 73
- **UUID:** C0E7A8FCF0E83E42B41416BAD0691019
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:20Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| UsageDate | `Date` | 🚫 Not Null | - |
| FromDate | `Date` | 🚫 Not Null | - |
| Quantity | `Long Integer` | 🚫 Not Null | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:20Z*
