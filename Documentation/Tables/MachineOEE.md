---
layout : default
title : MachineOEE
parent : Tables
---
# MachineOEE

📊 **Overview:** 13 Fields | 3 Indexes

## ℹ️ Table Information

- **Table ID:** 89
- **UUID:** EDFCD4019448A2478EF7BDE89DD8498C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:08Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductionDate | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| Availability | `Boolean` | 🚫 Not Null | - |
| Performance | `Boolean` | 🚫 Not Null | - |
| Quality | `Boolean` | 🚫 Not Null | - |
| OEE | `Boolean` | 🚫 Not Null | - |
| GoodTime | `Boolean` | 🚫 Not Null | - |
| PlannedTime | `Boolean` | 🚫 Not Null | - |
| TargetTime | `Boolean` | - | - |
| ActualTime | `Boolean` | 🚫 Not Null | - |
| TotalPacked | `Undefined` | - | - |
| TotalMade | `Undefined` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `WorksOrder` | Keywords | regular | - |
| `ProductionDate` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:08Z*
