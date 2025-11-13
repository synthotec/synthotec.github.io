---
layout : default
title : Log
parent : Tables
---
# Log

📊 **Overview:** 5 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 125
- **UUID:** D76C2CDE837AD4459AD6DD1537723C7C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:56Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| Date | `Integer` | - | - |
| Time | `Long Integer` | - | - |
| Message | `String` (255) | - | - |
| Process | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** String
- **Constraints:** 🔑 Primary Key, ✨ Unique

---

#### Date

**Properties:**

- **Type:** Integer

---

#### Time

**Properties:**

- **Type:** Long Integer

---

#### Message

**Properties:**

- **Type:** String (max length: 255)

---

#### Process

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Date` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Date`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:56Z*
