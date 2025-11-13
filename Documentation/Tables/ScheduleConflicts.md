---
layout : default
title : ScheduleConflicts
parent : Tables
---
# ScheduleConflicts

📊 **Overview:** 5 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 56
- **UUID:** 8353139CDBF96844B048C722296C657C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:54Z

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
| Machines | `String` (255) | 🚫 Not Null | - |
| ConflictDate | `Integer` | 🚫 Not Null | - |
| ConflictType | `String` (255) | 🚫 Not Null | - |
| PartNames | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Machines

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ConflictDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ConflictType

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PartNames

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ConflictType` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ConflictType`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:54Z*
