---
layout : default
title : WheelPlan
parent : Tables
---
# WheelPlan

📊 **Overview:** 4 Fields | 5 Indexes

## ℹ️ Table Information

- **Table ID:** 72
- **UUID:** 0FCA2FC5DFE22B4BBA03615CB63249A2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:50Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (5)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Machine | `Date` | 🚫 Not Null | - |
| dDate | `Integer` | 🚫 Not Null | - |
| Planned | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `dDate` | B-Tree | regular | - |
| `dDate` | Keywords | regular | - |
| `Machine` | Keywords | regular | - |
| `Machine` | B-Tree | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [Schedule_Planner](../Forms/Schedule_Planner.md) - Data source for Schedule_Planner form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:50Z*
