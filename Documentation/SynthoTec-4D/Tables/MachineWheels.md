---
layout : default
title : MachineWheels
parent : Tables
---
# MachineWheels

📊 **Overview:** 28 Fields | 2 Indexes

## 📝 Description

🗨️ Configuration table defining production machine positions on planning wheels. Maps machines to wheel slots for visual scheduling interface.

## ℹ️ Table Information

- **Table ID:** 52
- **UUID:** 4E54F86DE90F56408B41789A54462C64
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:15Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (28)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Machine | `Integer` | 🚫 Not Null | - |
| AvgDailyHours | `Real` | 🚫 Not Null | - |
| MonHours | `Real` | 🚫 Not Null | - |
| TueHours | `Real` | 🚫 Not Null | - |
| WedHours | `Real` | 🚫 Not Null | - |
| ThursHours | `Real` | 🚫 Not Null | - |
| FriHours | `Real` | 🚫 Not Null | - |
| SatHours | `Real` | 🚫 Not Null | - |
| SunHours | `Real` | 🚫 Not Null | - |
| Weekend | `Boolean` | 🚫 Not Null | - |
| DaysLate | `Long Integer` | 🚫 Not Null | - |
| DaysEarly | `Long Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| RemainingHours | `Real` | 🚫 Not Null | - |
| AutoStatus | `Boolean` | 🚫 Not Null | - |
| SlowStatus | `Boolean` | 🚫 Not Null | - |
| MouldStatus | `String` (255) | 🚫 Not Null | - |
| TimeOpened | `String` (255) | 🚫 Not Null | - |
| TimeClosed | `String` (255) | 🚫 Not Null | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| Availability | `Real` | 🚫 Not Null | - |
| Performance | `Real` | 🚫 Not Null | - |
| Quality | `Real` | 🚫 Not Null | - |
| LastAudit | `String` (255) | 🚫 Not Null | - |
| StopCycleID | `Long Integer` | 🚫 Not Null | - |
| NextJobID | `Long Integer` | 🚫 Not Null | - |
| AwaitingSetter | `Integer` | 🚫 Not Null | - |
| Priority | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Machine` | Keywords | regular | - |

## 🔗 Related Items

### 📄 Forms

- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:15Z*
