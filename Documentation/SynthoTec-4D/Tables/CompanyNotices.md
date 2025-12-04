---
layout : default
title : CompanyNotices
parent : Tables
---
# CompanyNotices

📊 **Overview:** 11 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 61
- **UUID:** 015540DC6D91DB4182E6B439B2252CC2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:09Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Category | `String` (255) | 🚫 Not Null | - |
| Title | `String` (255) | 🚫 Not Null | - |
| Description | `String` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| ShowDuration | `Integer` | 🚫 Not Null | - |
| Image | `Picture` | 🚫 Not Null | - |
| Colour | `Long Integer` | 🚫 Not Null | - |
| ShowFrom | `Date` | 🚫 Not Null | - |
| ShowUntil | `Date` | 🚫 Not Null | - |
| Archived | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Archived` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [CompanyNotices](../Forms/CompanyNotices.md) - Data source for CompanyNotices form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:09Z*
