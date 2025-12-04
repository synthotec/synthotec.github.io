---
layout : default
title : WheelPlan
parent : Tables
---
# WheelPlan

📊 **Overview:** 4 Fields | 5 Indexes

## 📝 Description

🗨️ Historical planning table archiving completed wheel schedules. Preserves past planning wheel states for reference and analysis.

## ℹ️ Table Information

- **Table ID:** 72
- **UUID:** 0FCA2FC5DFE22B4BBA03615CB63249A2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:34Z

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
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Machine | `Long Integer` | 🚫 Not Null | - |
| dDate | `Date` | 🚫 Not Null | - |
| Planned | `Real` | 🚫 Not Null | - |

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
*Generated at: 2025-12-04T14:34:34Z*
