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
- **Generated:** 🕐 2025-11-13T02:35:24Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID_l** | `Date` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| Language_ID | `Date` | 🚫 Not Null | - |
| TagIdentifier_s | `String` (10) | 🚫 Not Null | - |
| TagText_txt | `String` | 🚫 Not Null | - |
| TagDescription_txt | `String` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, 🚫 Never Null

---

#### Language_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### TagIdentifier_s

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** 🚫 Never Null

---

#### TagText_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### TagDescription_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID_l` | Keywords | regular | ✨ Yes |
| `Language_ID` | Keywords | regular | - |
| `TagIdentifier_s` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Language_ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `TagIdentifier_s`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `LanguageENtity` | [Language](Language.md) | `Language_ID` → `ID_l` | Active |

### Detailed Information

#### LanguageENtity

**Links to:** [Language](Language.md)

- **Source Field:** `Language_ID`
- **Destination Field:** `ID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:24Z*
