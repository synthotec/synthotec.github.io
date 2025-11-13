---
layout : default
title : ChangeLog
parent : Tables
---
# ChangeLog

📊 **Overview:** 6 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 44
- **UUID:** FCFA50991EE10548874C7FB40849B15D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:31Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Date | `Integer` | 🚫 Not Null | - |
| Section | `String` (255) | 🚫 Not Null | - |
| Type | `String` (255) | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |
| ChangedBy | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Section

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Type

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Description

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ChangedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:31Z*
