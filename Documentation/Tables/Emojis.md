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
- **Generated:** 🕐 2025-11-13T16:09:28Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Emoji | `String` (255) | ✨ Unique | - |
| Name | `String` (255) | - | - |
| Category | `String` (255) | - | - |
| Banned | `Real` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Emoji` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ProductSelection` | [Product](Product.md) | `EmojiID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:09:28Z*
