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
- **Generated:** 🕐 2025-11-13T23:19:20Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (5)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Table | `Date` | 🚫 Not Null | - |
| Field | `Date` | 🚫 Not Null | - |
| PrimaryKey | `Date` | 🚫 Not Null | - |
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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:20Z*
