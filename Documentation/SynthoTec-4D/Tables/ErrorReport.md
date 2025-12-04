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
- **Generated:** 🕐 2025-12-03T16:25:10Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| FirstOccurrence | `String` (255) | - | - |
| LastOccurrence | `String` (255) | - | - |
| Occurrences | `Integer` | - | - |
| Digest | `String` (255) | - | - |
| ErrorObject | `Object` | - | - |
| SendSlack | `Boolean` | - | - |
| SendEmail | `Boolean` | - | - |
| SlackMessageID | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Digest` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📦 Classes

- [ErrorReport](../Classes/ErrorReport.md) - ORDA DataClass class for ErrorReport table
- [ErrorReportEntity](../Classes/ErrorReportEntity.md) - ORDA Entity class for ErrorReport table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:25:10Z*
