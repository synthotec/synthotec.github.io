---
layout : default
title : CalculatedValues
parent : Tables
---
# CalculatedValues

📊 **Overview:** 4 Fields | 2 Indexes

## 📝 Description

🗨️ Configuration table storing pre-calculated values and lookup tables for performance optimization. Used for complex calculations and conversion tables.

## ℹ️ Table Information

- **Table ID:** 104
- **UUID:** C375BFE8D695A44DAF7A1BB4569FEEE0
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:04Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| ValueName | `String` (255) | 🚫 Not Null | - |
| PrimaryKey | `Long Integer` | 🚫 Not Null | - |
| Value | `Object` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ValueName` | B-Tree | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:04Z*
