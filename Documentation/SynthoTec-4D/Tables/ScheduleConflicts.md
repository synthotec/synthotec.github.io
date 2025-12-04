---
layout : default
title : ScheduleConflicts
parent : Tables
---
# ScheduleConflicts

📊 **Overview:** 5 Fields | 2 Indexes

## 📝 Description

🗨️ Alert table flagging production scheduling conflicts. Identifies overlapping machine assignments, capacity violations, and date issues.

## ℹ️ Table Information

- **Table ID:** 56
- **UUID:** 8353139CDBF96844B048C722296C657C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:18Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Machines | `String` (255) | 🚫 Not Null | - |
| ConflictDate | `Date` | 🚫 Not Null | - |
| ConflictType | `String` (255) | 🚫 Not Null | - |
| PartNames | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ConflictType` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:18Z*
