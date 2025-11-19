---
layout : default
title : QualitySystemResults
parent : Tables
---
# QualitySystemResults

📊 **Overview:** 22 Fields | 4 Indexes

## ℹ️ Table Information

- **Table ID:** 99
- **UUID:** C46FD557FC0E4A4E995DC54102D0087E
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:17Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (22)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| System | `String` (255) | 🚫 Not Null | - |
| Procedure | `String` (255) | 🚫 Not Null | - |
| Subject | `String` (255) | 🚫 Not Null | - |
| Result | `Boolean` | 🚫 Not Null | - |
| TargetMin | `Boolean` | 🚫 Not Null | - |
| TargetMax | `Boolean` | 🚫 Not Null | - |
| Completed | `Real` | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |
| CompletedDate | `Integer` | 🚫 Not Null | - |
| CompletedTime | `Long Integer` | 🚫 Not Null | - |
| AdditionalDetail | `String` (255) | 🚫 Not Null | - |
| Comment | `String` (255) | 🚫 Not Null | - |
| ResultPassStatus | `Real` | 🚫 Not Null | - |
| AdditionalID | `Date` | 🚫 Not Null | - |
| SubjectID | `Date` | 🚫 Not Null | - |
| Confirmed | `Real` | 🚫 Not Null | - |
| ConfirmedDate | `Integer` | 🚫 Not Null | - |
| ConfirmedTime | `Long Integer` | 🚫 Not Null | - |
| ConfirmedBy | `String` (255) | 🚫 Not Null | - |
| ProcedureOrder | `Picture` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Completed` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `System` | Keywords | regular | - |

## 🔗 Related Items

### 📦 Classes

- [QualitySystemResults](../Classes/QualitySystemResults.md) - ORDA DataClass class for QualitySystemResults table

### 📄 Forms

- [QualitySystemResults](../Forms/QualitySystemResults.md) - Data source for QualitySystemResults form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:17Z*
