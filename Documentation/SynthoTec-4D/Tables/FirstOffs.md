---
layout : default
title : FirstOffs
parent : Tables
---
# FirstOffs

📊 **Overview:** 23 Fields | 1 Indexes

## 📝 Description

🗨️ Quality control table recording first article inspections at production setup. Captures dimensional checks, weights, and approval before full run.

## ℹ️ Table Information

- **Table ID:** 60
- **UUID:** 34BFB440508D4E468E6B86A28637B6DF
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:22Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (23)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |
| Method | `String` (255) | 🚫 Not Null | - |
| Cav1 | `Real` | 🚫 Not Null | - |
| Cav2 | `Real` | 🚫 Not Null | - |
| Cav3 | `Real` | 🚫 Not Null | - |
| Cav4 | `Real` | 🚫 Not Null | - |
| Cav5 | `Real` | 🚫 Not Null | - |
| Cav6 | `Real` | 🚫 Not Null | - |
| Cav7 | `Real` | 🚫 Not Null | - |
| Cav8 | `Real` | 🚫 Not Null | - |
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

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:22Z*
