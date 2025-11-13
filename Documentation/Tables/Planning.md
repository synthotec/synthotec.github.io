---
layout : default
title : Planning
parent : Tables
---
# Planning

📊 **Overview:** 13 Fields | 4 Indexes

## ℹ️ Table Information

- **Table ID:** 69
- **UUID:** 85B429DD73F4624CB829A1662373A124
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:48:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Product_ID | `Date` | 🚫 Not Null | - |
| Hours | `Boolean` | 🚫 Not Null | - |
| fQTY | `Date` | 🚫 Not Null | - |
| tRoute | `Picture` | 🚫 Not Null | - |
| tImps | `Boolean` | 🚫 Not Null | - |
| tCycle | `Boolean` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| Profile | `String` (255) | 🚫 Not Null | - |
| SnapDate | `Integer` | 🚫 Not Null | - |
| ShotWeight | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `SnapDate` | Cluster | regular | - |
| `Profile` | Cluster | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `tRoute` | Cluster | regular | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:45Z*
