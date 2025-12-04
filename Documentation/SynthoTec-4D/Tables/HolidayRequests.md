---
layout : default
title : HolidayRequests
parent : Tables
---
# HolidayRequests

📊 **Overview:** 7 Fields | 2 Indexes

## 📝 Description

🗨️ HR transaction table managing staff holiday and time-off requests. Tracks request dates, approval status, and remaining holiday allowances.

## ℹ️ Table Information

- **Table ID:** 79
- **UUID:** 26B56558930CE9449F07B020C86BEA93
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:41Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StaffName | `String` (255) | 🚫 Not Null | - |
| FirstDate | `Date` | 🚫 Not Null | - |
| LastDate | `Date` | 🚫 Not Null | - |
| Days | `Real` | 🚫 Not Null | - |
| Comment | `String` (255) | 🚫 Not Null | - |
| Status | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Status` | Keywords | regular | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:41Z*
