---
layout : default
title : Error
parent : Tables
---
# Error

📊 **Overview:** 7 Fields | 2 Indexes | 1 One-to-Many Relations

## 📝 Description

🗨️ System logging table capturing application errors and exceptions. Records error details, stack traces, and context for debugging.

## ℹ️ Table Information

- **Table ID:** 131
- **UUID:** AF1DEE5EA76ACE42AEFB98922A785EEB
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:30Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| Code | `Long Integer` | - | - |
| Method | `String` (255) | - | - |
| Line | `Long Integer` | - | - |
| Formula | `String` (255) | - | - |
| GithubIssue | `Object` | - | - |
| Suppress | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Suppress` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ErrorDetailSelection` | [ErrorDetail](ErrorDetail.md) | `ErrorID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Error](../Classes/Error.md) - ORDA DataClass class for Error table
- [ErrorEntity](../Classes/ErrorEntity.md) - ORDA Entity class for Error table

### 📄 Forms

- [Errors](../Forms/Errors.md) - Data source for Errors form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:30Z*
