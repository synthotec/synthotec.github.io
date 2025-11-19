---
layout : default
title : MachineWheels
parent : Tables
---
# MachineWheels

📊 **Overview:** 28 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 52
- **UUID:** 4E54F86DE90F56408B41789A54462C64
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:29Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (28)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Machine | `Picture` | 🚫 Not Null | - |
| AvgDailyHours | `Boolean` | 🚫 Not Null | - |
| MonHours | `Boolean` | 🚫 Not Null | - |
| TueHours | `Boolean` | 🚫 Not Null | - |
| WedHours | `Boolean` | 🚫 Not Null | - |
| ThursHours | `Boolean` | 🚫 Not Null | - |
| FriHours | `Boolean` | 🚫 Not Null | - |
| SatHours | `Boolean` | 🚫 Not Null | - |
| SunHours | `Boolean` | 🚫 Not Null | - |
| Weekend | `Real` | 🚫 Not Null | - |
| DaysLate | `Date` | 🚫 Not Null | - |
| DaysEarly | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| RemainingHours | `Boolean` | 🚫 Not Null | - |
| AutoStatus | `Real` | 🚫 Not Null | - |
| SlowStatus | `Real` | 🚫 Not Null | - |
| MouldStatus | `String` (255) | 🚫 Not Null | - |
| TimeOpened | `String` (255) | 🚫 Not Null | - |
| TimeClosed | `String` (255) | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| Availability | `Boolean` | 🚫 Not Null | - |
| Performance | `Boolean` | 🚫 Not Null | - |
| Quality | `Boolean` | 🚫 Not Null | - |
| LastAudit | `String` (255) | 🚫 Not Null | - |
| StopCycleID | `Date` | 🚫 Not Null | - |
| NextJobID | `Date` | 🚫 Not Null | - |
| AwaitingSetter | `Picture` | 🚫 Not Null | - |
| Priority | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Machine` | Keywords | regular | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:29Z*
