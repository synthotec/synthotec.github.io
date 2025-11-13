---
layout : default
title : Emojis
parent : Tables
---
# Emojis

📊 **Overview:** 5 Fields | 2 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 111
- **UUID:** D8CAAE9B0978364D94111448E593405B
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:43Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Emoji | `String` (255) | ✨ Unique | - |
| Name | `String` (255) | - | - |
| Category | `String` (255) | - | - |
| Banned | `Real` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Emoji

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** ✨ Unique

---

#### Name

**Properties:**

- **Type:** String (max length: 255)

---

#### Category

**Properties:**

- **Type:** String (max length: 255)

---

#### Banned

**Properties:**

- **Type:** Real

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Emoji` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Emoji` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ProductSelection` | [Product](Product.md) | `EmojiID` → `ID` | Active |

### Detailed Information

#### ProductSelection

**Links from:** [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `EmojiID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:43Z*
