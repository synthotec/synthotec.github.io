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
- **Generated:** 🕐 2025-12-03T16:24:35Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductionDate | `Date` | 🚫 Not Null | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| Availability | `Real` | 🚫 Not Null | - |
| Performance | `Real` | 🚫 Not Null | - |
| Quality | `Real` | 🚫 Not Null | - |
| OEE | `Real` | 🚫 Not Null | - |
| GoodTime | `Real` | 🚫 Not Null | - |
| PlannedTime | `Real` | 🚫 Not Null | - |
| TargetTime | `Real` | - | - |
| ActualTime | `Real` | 🚫 Not Null | - |
| TotalPacked | `Integer` | - | - |
| TotalMade | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `WorksOrder` | Keywords | regular | - |
| `ProductionDate` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [%2ATempOEE](../Forms/%2ATempOEE.md) - Data source for %2ATempOEE form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:35Z*
