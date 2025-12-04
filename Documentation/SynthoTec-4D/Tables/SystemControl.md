---
layout : default
title : SystemControl
parent : Tables
---
# SystemControl

📊 **Overview:** 13 Fields | 1 Indexes

## 📝 Description

🗨️ Configuration table storing system-wide settings, preferences, and control parameters. Single-record table managing global application behavior.

## ℹ️ Table Information

- **Table ID:** 28
- **UUID:** 033E20DBAC212B4389E5C70620881ED8
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:33:54Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| NSKLabelsPerSet_l | `Long Integer` | 🚫 Not Null | - |
| NoOfPackers_l | `Long Integer` | 🚫 Not Null | - |
| WIPStockValuePC_i | `Integer` | 🚫 Not Null | - |
| QuarantinedStockValuePC_i | `Integer` | 🚫 Not Null | - |
| ReturnedStockValuePC_i | `Integer` | 🚫 Not Null | - |
| FinishedStockValuePC_i | `Integer` | 🚫 Not Null | - |
| MaxPOCost_r | `Real` | 🚫 Not Null | - |
| POLimitGroup_s | `String` (30) | 🚫 Not Null | - |
| ThreeMnthStkChk | `Boolean` | 🚫 Not Null | - |
| OldNew_RouteCardLayout | `Boolean` | 🚫 Not Null | - |
| gross_wgt_label | `Boolean` | 🚫 Not Null | - |
| Machine_Hourly_Rate | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:33:54Z*
