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
- **Generated:** 🕐 2025-12-03T16:23:39Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (5)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product_ID | `Long Integer` | ⚠️ Required, 🚫 Not Null, ��� Not Modifiable | - |
| Works_Order | `Long Integer` | ⚠️ Required, 🚫 Not Null | - |
| Chamber_No | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Box_Number | `Real` | 🚫 Not Null | - |
| Actual_Time | `Integer` | 🚫 Not Null | - |
| Wet_Date | `Date` | 🚫 Not Null | - |
| TopUp_Weight | `Real` | 🚫 Not Null | - |
| Wet_Initals | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Dry_Weight | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Wet_Weight | `Real` | 🚫 Not Null | - |
| TopUp_Date | `Date` | 🚫 Not Null | - |
| TopUp_Initials | `String` (5) | 🚫 Not Null | - |
| Moisture_Percent | `Real` | 🚫 Not Null | - |
| TopUp_Percent | `Real` | 🚫 Not Null | - |
| Does_Need_TopUp | `Boolean` | 🚫 Not Null | - |
| Part_No | `String` (20) | ⚠️ Required, 🚫 Not Null | - |
| Second_TopUp | `Boolean` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

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
*Generated at: 2025-12-03T16:23:39Z*
