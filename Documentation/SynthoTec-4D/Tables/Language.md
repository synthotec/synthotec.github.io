---
layout : default
title : Language
parent : Tables
---
# Language

📊 **Overview:** 2 Fields | 1 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 32
- **UUID:** 4F6BBCF8E9304244A5440EF31A025AD4
- **Primary Key:** 🔑 `ID_l`
- **Generated:** 🕐 2025-12-03T16:23:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (2)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID_l** | `Long Integer` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| Language_s | `String` (30) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID_l` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `LanguageTagSelection` | [LanguageTag](LanguageTag.md) | `Language_ID` → `ID_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [LanguageEntity](../Classes/LanguageEntity.md) - ORDA Entity class for Language table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:45Z*
