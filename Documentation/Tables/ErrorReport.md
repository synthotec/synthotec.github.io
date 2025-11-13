---
layout : default
title : ErrorReport
parent : Tables
---
# ErrorReport

📊 **Overview:** 9 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 128
- **UUID:** 00591B1C82FBA248968703B6704134D1
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:20Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| FirstOccurrence | `String` (255) | - | - |
| LastOccurrence | `String` (255) | - | - |
| Occurrences | `Undefined` | - | - |
| Digest | `String` (255) | - | - |
| ErrorObject | `Unknown (21)` | - | - |
| SendSlack | `Real` | - | - |
| SendEmail | `Real` | - | - |
| SlackMessageID | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### FirstOccurrence

**Properties:**

- **Type:** String (max length: 255)

---

#### LastOccurrence

**Properties:**

- **Type:** String (max length: 255)

---

#### Occurrences

**Properties:**

- **Type:** Undefined

---

#### Digest

**Properties:**

- **Type:** String (max length: 255)

---

#### ErrorObject

**Properties:**

- **Type:** Unknown (21)

---

#### SendSlack

**Properties:**

- **Type:** Real

---

#### SendEmail

**Properties:**

- **Type:** Real

---

#### SlackMessageID

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Digest` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Digest`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:37:20Z*
