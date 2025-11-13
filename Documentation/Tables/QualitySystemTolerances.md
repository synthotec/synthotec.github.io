---
layout : default
title : QualitySystemTolerances
parent : Tables
---
# QualitySystemTolerances

📊 **Overview:** 7 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 107
- **UUID:** C3B026087195274EBE4A71B14374D159
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:40Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| System | `String` (255) | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Type | `Date` | 🚫 Not Null | - |
| Tolerance | `Boolean` | 🚫 Not Null | - |
| Machine | `Date` | 🚫 Not Null | - |
| ModifiedBy | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** String
- **Constraints:** 🔑 Primary Key, ✨ Unique

---

#### System

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Type

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Tolerance

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Machine

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ModifiedBy

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
*Generated at: 2025-11-13T02:36:40Z*
