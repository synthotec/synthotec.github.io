---
layout : default
title : SystemControl
parent : Tables
---
# SystemControl

📊 **Overview:** 13 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 28
- **UUID:** 033E20DBAC212B4389E5C70620881ED8
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:08Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| NSKLabelsPerSet_l | `Date` | 🚫 Not Null | - |
| NoOfPackers_l | `Date` | 🚫 Not Null | - |
| WIPStockValuePC_i | `Picture` | 🚫 Not Null | - |
| QuarantinedStockValuePC_i | `Picture` | 🚫 Not Null | - |
| ReturnedStockValuePC_i | `Picture` | 🚫 Not Null | - |
| FinishedStockValuePC_i | `Picture` | 🚫 Not Null | - |
| MaxPOCost_r | `Boolean` | 🚫 Not Null | - |
| POLimitGroup_s | `String` (30) | 🚫 Not Null | - |
| ThreeMnthStkChk | `Real` | 🚫 Not Null | - |
| OldNew_RouteCardLayout | `Real` | 🚫 Not Null | - |
| gross_wgt_label | `Real` | 🚫 Not Null | - |
| Machine_Hourly_Rate | `Boolean` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:08Z*
