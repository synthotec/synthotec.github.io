---
layout : default
title : StaffActivity
parent : Tables
---
# StaffActivity

📊 **Overview:** 4 Fields | 1 Indexes

## 📝 Description

🗨️ Audit table logging staff actions and system usage. Tracks login/logout times, activities performed, and user engagement for reporting.

## ℹ️ Table Information

- **Table ID:** 75
- **UUID:** D37308D78941F644A7EC6CAE21724BD1
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:37Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StaffName | `String` (255) | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| StaffID | `Long Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [Staff](../Forms/Staff.md) - Data source for Staff form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:37Z*
