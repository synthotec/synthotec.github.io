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
- **Generated:** 🕐 2025-11-13T16:08:43Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Category | `String` (255) | 🚫 Not Null | - |
| Title | `String` (255) | 🚫 Not Null | - |
| Description | `String` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| ShowDuration | `Picture` | 🚫 Not Null | - |
| Image | `Picture` | 🚫 Not Null | - |
| Colour | `Date` | 🚫 Not Null | - |
| ShowFrom | `Integer` | 🚫 Not Null | - |
| ShowUntil | `Integer` | 🚫 Not Null | - |
| Archived | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Archived` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:43Z*
