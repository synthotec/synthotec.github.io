---
layout : default
title : (Copy_of_PatrolInspection)
parent : Tables
---
# (Copy_of_PatrolInspection)

📊 **Overview:** 28 Fields | 1 Indexes

## 📝 Description

🗨️ Legacy quality control table - archived copy of patrol inspection data. Replaced by QualitySystemResults.

## ℹ️ Table Information

- **Table ID:** 96
- **UUID:** CDC6757D6C25C14A8C2CAA01079A6600
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (28)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Integer` | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |
| Method | `String` (255) | 🚫 Not Null | - |
| Cav1 | `String` (255) | 🚫 Not Null | - |
| Cav2 | `String` (255) | 🚫 Not Null | - |
| Cav3 | `String` (255) | 🚫 Not Null | - |
| Cav4 | `String` (255) | 🚫 Not Null | - |
| Cav5 | `String` (255) | 🚫 Not Null | - |
| Cav6 | `String` (255) | 🚫 Not Null | - |
| Cav7 | `String` (255) | 🚫 Not Null | - |
| Cav8 | `String` (255) | 🚫 Not Null | - |
| MethodCompleted | `Boolean` | 🚫 Not Null | - |
| DateCompleted | `Date` | 🚫 Not Null | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| Cav9 | `String` (255) | 🚫 Not Null | - |
| Cav10 | `String` (255) | 🚫 Not Null | - |
| Cav11 | `String` (255) | 🚫 Not Null | - |
| Cav12 | `String` (255) | 🚫 Not Null | - |
| Cav13 | `String` (255) | 🚫 Not Null | - |
| Cav14 | `String` (255) | 🚫 Not Null | - |
| Cav15 | `String` (255) | 🚫 Not Null | - |
| Cav16 | `String` (255) | 🚫 Not Null | - |
| TimeCompleted | `Time` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| WriteBy | `String` (255) | 🚫 Not Null | - |
| DateWriteBy | `Date` | 🚫 Not Null | - |
| TimeWriteBy | `Time` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:57Z*
