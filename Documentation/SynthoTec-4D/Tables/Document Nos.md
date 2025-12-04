---
layout : default
title : Document Nos
parent : Tables
---
# Document Nos

📊 **Overview:** 14 Fields | 1 Indexes

## 📝 Description

🗨️ Configuration table managing auto-incrementing document number sequences for various document types (CofC, invoices, orders, etc.). Ensures unique numbering across system.

## ℹ️ Table Information

- **Table ID:** 7
- **UUID:** 6BC1D99CA275574B8B75504F16B14CB2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:33:35Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (14)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Cert_Of_Conformance_No | `Integer` | 🚫 Not Null | - |
| Advice Note No | `Integer` | 🚫 Not Null | - |
| Petes No | `Integer` | 🚫 Not Null | - |
| Date spare5 | `Date` | 🚫 Not Null | - |
| C Code Spare | `String` (3) | 🚫 Not Null | - |
| no ord spare2 | `Integer` | 🚫 Not Null | - |
| Balance | `Real` | 🚫 Not Null | - |
| totalflag | `Boolean` | 🚫 Not Null | - |
| Ord No spare3 | `String` (15) | 🚫 Not Null | - |
| Cust Name spare | `String` (25) | 🚫 Not Null | - |
| Works No spare6 | `Integer` | 🚫 Not Null | - |
| Datepriceupdate | `Date` | 🚫 Not Null | - |
| HARtrays1E | `Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:33:35Z*
