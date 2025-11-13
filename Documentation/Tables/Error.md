---
layout : default
title : Error
parent : Tables
---
# Error

📊 **Overview:** 7 Fields | 2 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 131
- **UUID:** AF1DEE5EA76ACE42AEFB98922A785EEB
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| Code | `Date` | - | - |
| Method | `String` (255) | - | - |
| Line | `Date` | - | - |
| Formula | `String` (255) | - | - |
| GithubIssue | `Object` | - | - |
| Suppress | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Suppress` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ErrorDetailSelection` | [ErrorDetail](ErrorDetail.md) | `ErrorID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:57Z*
