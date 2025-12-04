---
layout : default
title : Unique_Codes
parent : Tables
---
# Unique_Codes

📊 **Overview:** 8 Fields | 4 Indexes

## ℹ️ Table Information

- **Table ID:** 17
- **UUID:** 841927B91F0A984697E1A0A7E2C95BA9
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:31Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| TableNo | `Integer` | 🚫 Not Null | - |
| UniqueCode | `Long Integer` | 🚫 Not Null | - |
| IsItMaster | `Boolean` | 🚫 Not Null | - |
| SearchParameter | `String` (11) | 🚫 Not Null | - |
| Display_b | `Boolean` | 🚫 Not Null | - |
| Label_s | `String` (32) | 🚫 Not Null | - |
| FieldNo_l | `Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |
| `IsItMaster` | Keywords | regular | - |
| `FieldNo_l` | Keywords | regular | - |
| `TableNo` | Keywords | regular | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:31Z*
