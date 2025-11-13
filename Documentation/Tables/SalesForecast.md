---
layout : default
title : SalesForecast
parent : Tables
---
# SalesForecast

📊 **Overview:** 22 Fields | 7 Indexes

## ℹ️ Table Information

- **Table ID:** 49
- **UUID:** 0412FF273154D14EA78AFDEC1CD85D3D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:08:32Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (22)
- [🔍 Indexes](#-indexes) (7)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ProductID | `Date` | 🚫 Not Null | - |
| fYear | `Picture` | 🚫 Not Null | - |
| January | `Undefined` | 🚫 Not Null | - |
| February | `Undefined` | 🚫 Not Null | - |
| March | `Undefined` | 🚫 Not Null | - |
| April | `Undefined` | 🚫 Not Null | - |
| May | `Undefined` | 🚫 Not Null | - |
| June | `Undefined` | 🚫 Not Null | - |
| July | `Undefined` | 🚫 Not Null | - |
| August | `Undefined` | 🚫 Not Null | - |
| September | `Undefined` | 🚫 Not Null | - |
| October | `Undefined` | 🚫 Not Null | - |
| November | `Undefined` | 🚫 Not Null | - |
| December | `Undefined` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| LastEdited | `Integer` | 🚫 Not Null | - |
| YearlyVolume | `Undefined` | 🚫 Not Null | - |
| SnapShot | `Real` | 🚫 Not Null | - |
| SnapDate | `Integer` | 🚫 Not Null | - |
| CurrentBacklog | `Undefined` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `fYear` | Cluster | regular | - |
| `ProductID` | Cluster | regular | - |
| `SnapDate` | Cluster | regular | - |
| `Customer` | Cluster | regular | - |
| `PartName` | Cluster | regular | - |
| `SnapShot` | Cluster | regular | - |
| `ID` | B-Tree | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:32Z*
