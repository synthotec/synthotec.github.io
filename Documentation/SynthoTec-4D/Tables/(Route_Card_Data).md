---
layout : default
title : (Route_Card_Data)
parent : Tables
---
# (Route_Card_Data)

📊 **Overview:** 18 Fields | 5 Indexes

## ℹ️ Table Information

- **Table ID:** 26
- **UUID:** AB1C481C69AFC94D924C5E73D8EC1283
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:06Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (5)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product_ID | `Date` | ⚠️ Required, 🚫 Not Null, ��� Not Modifiable | - |
| Works_Order | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Chamber_No | `Picture` | ⚠️ Required, 🚫 Not Null | - |
| Box_Number | `Boolean` | 🚫 Not Null | - |
| Actual_Time | `Picture` | 🚫 Not Null | - |
| Wet_Date | `Integer` | 🚫 Not Null | - |
| TopUp_Weight | `Boolean` | 🚫 Not Null | - |
| Wet_Initals | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Dry_Weight | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Wet_Weight | `Boolean` | 🚫 Not Null | - |
| TopUp_Date | `Integer` | 🚫 Not Null | - |
| TopUp_Initials | `String` (5) | 🚫 Not Null | - |
| Moisture_Percent | `Boolean` | 🚫 Not Null | - |
| TopUp_Percent | `Boolean` | 🚫 Not Null | - |
| Does_Need_TopUp | `Real` | 🚫 Not Null | - |
| Part_No | `String` (20) | ⚠️ Required, 🚫 Not Null | - |
| Second_TopUp | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Product_ID` | Keywords | regular | - |
| `Chamber_No` | Keywords | regular | - |
| `Works_Order` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Part_No` | Keywords | regular | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:06Z*
