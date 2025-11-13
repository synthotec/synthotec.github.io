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
- **Generated:** 🕐 2025-11-13T02:35:23Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (2)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID_l** | `Date` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| Language_s | `String` (30) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, 🚫 Never Null

---

#### Language_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID_l` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `LanguageTagSelection` | [LanguageTag](LanguageTag.md) | `Language_ID` → `ID_l` | Active |

### Detailed Information

#### LanguageTagSelection

**Links from:** [LanguageTag](LanguageTag.md)

- **Source Table:** `LanguageTag`
- **Source Field:** `Language_ID`
- **This Table Field:** `ID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:23Z*
