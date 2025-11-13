---
layout : default
title : Translation
parent : Tables
---
# Translation

📊 **Overview:** 5 Fields | 3 Indexes

## ℹ️ Table Information

- **Table ID:** 93
- **UUID:** FB3EF960B67EC1469BFEF51C80EEDF92
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:28Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (3)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Process | `String` (255) | 🚫 Not Null | - |
| OriginalText | `String` | 🚫 Not Null | - |
| TranslatedText | `String` | 🚫 Not Null | - |
| LastModified | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Process

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### OriginalText

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### TranslatedText

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### LastModified

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `OriginalText` | Keywords | regular | - |
| `Process` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `OriginalText`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Process`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:28Z*
