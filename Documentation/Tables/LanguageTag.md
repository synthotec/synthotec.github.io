---
layout : default
title : LanguageTag
parent : Tables
---
# LanguageTag

📊 **Overview:** 5 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 33
- **UUID:** C687C116DFD6DE43AE003396315A8A4D
- **Primary Key:** 🔑 `ID_l`
- **Generated:** 🕐 2025-11-13T02:48:08Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID_l** | `Date` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| Language_ID | `Date` | 🚫 Not Null | - |
| TagIdentifier_s | `String` (10) | 🚫 Not Null | - |
| TagText_txt | `String` | 🚫 Not Null | - |
| TagDescription_txt | `String` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID_l` | Keywords | regular | ✨ Yes |
| `Language_ID` | Keywords | regular | - |
| `TagIdentifier_s` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `LanguageENtity` | [Language](Language.md) | `Language_ID` → `ID_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [LanguageTagEntity](../Classes/LanguageTagEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:08Z*
