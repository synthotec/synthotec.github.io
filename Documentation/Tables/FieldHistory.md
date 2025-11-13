---
layout : default
title : FieldHistory
parent : Tables
---
# FieldHistory

📊 **Overview:** 7 Fields | 5 Indexes

## ℹ️ Table Information

- **Table ID:** 102
- **UUID:** D4E78D9BFB953A4889052AAB5F6072AF
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:36Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (5)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Table | `Date` | 🚫 Not Null | - |
| Field | `Date` | 🚫 Not Null | - |
| PrimaryKey | `Date` | 🚫 Not Null | - |
| ChangedBy | `String` (255) | 🚫 Not Null | - |
| ChangedDateTime | `String` (255) | 🚫 Not Null | - |
| Value | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Table

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Field

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PrimaryKey

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ChangedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ChangedDateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Value

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `PrimaryKey` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Table` | B-Tree | regular | - |
| `Table` | Keywords | regular | - |
| `Field` | Keywords | regular | - |

### Detailed Information

- **Field:** `PrimaryKey`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Table`
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `Table`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Field`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:36Z*
