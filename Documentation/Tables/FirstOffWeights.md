---
layout : default
title : FirstOffWeights
parent : Tables
---
# FirstOffWeights

📊 **Overview:** 5 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 46
- **UUID:** B81AB99DDF831D4C90A3E757E0528D32
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Object | `String` (255) | 🚫 Not Null | - |
| Weight | `Boolean` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| StandardWeight | `Boolean` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Object

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### StandardWeight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `WorksOrder` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:45Z*
