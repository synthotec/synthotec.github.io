---
layout : default
title : Planning
parent : Tables
---
# Planning

📊 **Overview:** 13 Fields | 4 Indexes

## 📝 Description

🗨️ Core planning table managing production scheduling and machine allocation. Assigns works orders to machines with start/end times.

## ℹ️ Table Information

- **Table ID:** 69
- **UUID:** 85B429DD73F4624CB829A1662373A124
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:31Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Product_ID | `Long Integer` | 🚫 Not Null | - |
| Hours | `Real` | 🚫 Not Null | - |
| fQTY | `Long Integer` | 🚫 Not Null | - |
| tRoute | `Integer` | 🚫 Not Null | - |
| tImps | `Real` | 🚫 Not Null | - |
| tCycle | `Real` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| Profile | `String` (255) | 🚫 Not Null | - |
| SnapDate | `Date` | 🚫 Not Null | - |
| ShotWeight | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `SnapDate` | Cluster | regular | - |
| `Profile` | Cluster | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `tRoute` | Cluster | regular | - |

## 🔗 Related Items

### 📄 Forms

- [CapacityPlanning](../Forms/CapacityPlanning.md) - Data source for CapacityPlanning form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:31Z*
