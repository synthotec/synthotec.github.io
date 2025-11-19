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
- **Generated:** 🕐 2025-11-13T23:17:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| TableNo | `Picture` | 🚫 Not Null | - |
| UniqueCode | `Date` | 🚫 Not Null | - |
| IsItMaster | `Real` | 🚫 Not Null | - |
| SearchParameter | `String` (11) | 🚫 Not Null | - |
| Display_b | `Real` | 🚫 Not Null | - |
| Label_s | `String` (32) | 🚫 Not Null | - |
| FieldNo_l | `Picture` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |
| `IsItMaster` | Keywords | regular | - |
| `FieldNo_l` | Keywords | regular | - |
| `TableNo` | Keywords | regular | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:57Z*
