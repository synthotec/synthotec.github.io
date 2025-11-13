---
layout : default
title : ErrorReport
parent : Tables
---
# ErrorReport

📊 **Overview:** 9 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 128
- **UUID:** 00591B1C82FBA248968703B6704134D1
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:54Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| FirstOccurrence | `String` (255) | - | - |
| LastOccurrence | `String` (255) | - | - |
| Occurrences | `Undefined` | - | - |
| Digest | `String` (255) | - | - |
| ErrorObject | `Object` | - | - |
| SendSlack | `Real` | - | - |
| SendEmail | `Real` | - | - |
| SlackMessageID | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Digest` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📦 Classes

- [ErrorReport](../Classes/ErrorReport.md) - DataClass class
- [ErrorReportEntity](../Classes/ErrorReportEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:54Z*
