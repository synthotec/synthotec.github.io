---
layout : default
title : QualitySystemResults
parent : Tables
---
# QualitySystemResults

📊 **Overview:** 22 Fields | 4 Indexes

## 📝 Description

🗨️ Transaction table storing quality inspection measurement results. Records dimensional checks, test values, pass/fail status, and inspector details.

## ℹ️ Table Information

- **Table ID:** 99
- **UUID:** C46FD557FC0E4A4E995DC54102D0087E
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:00Z

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
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| System | `String` (255) | 🚫 Not Null | - |
| Procedure | `String` (255) | 🚫 Not Null | - |
| Subject | `String` (255) | 🚫 Not Null | - |
| Result | `Real` | 🚫 Not Null | - |
| TargetMin | `Real` | 🚫 Not Null | - |
| TargetMax | `Real` | 🚫 Not Null | - |
| Completed | `Boolean` | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |
| CompletedDate | `Date` | 🚫 Not Null | - |
| CompletedTime | `Time` | 🚫 Not Null | - |
| AdditionalDetail | `String` (255) | 🚫 Not Null | - |
| Comment | `String` (255) | 🚫 Not Null | - |
| ResultPassStatus | `Boolean` | 🚫 Not Null | - |
| AdditionalID | `Long Integer` | 🚫 Not Null | - |
| SubjectID | `Long Integer` | 🚫 Not Null | - |
| Confirmed | `Boolean` | 🚫 Not Null | - |
| ConfirmedDate | `Date` | 🚫 Not Null | - |
| ConfirmedTime | `Time` | 🚫 Not Null | - |
| ConfirmedBy | `String` (255) | 🚫 Not Null | - |
| ProcedureOrder | `Integer` | 🚫 Not Null | - |

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
*Generated at: 2025-12-04T14:35:00Z*
