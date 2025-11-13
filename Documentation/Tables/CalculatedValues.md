---
layout : default
title : CalculatedValues
parent : Tables
---
# CalculatedValues

📊 **Overview:** 4 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 104
- **UUID:** C375BFE8D695A44DAF7A1BB4569FEEE0
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:37Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| ValueName | `String` (255) | 🚫 Not Null | - |
| PrimaryKey | `Date` | 🚫 Not Null | - |
| Value | `Unknown (21)` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** String
- **Constraints:** 🔑 Primary Key, ✨ Unique

---

#### ValueName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PrimaryKey

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Value

**Properties:**

- **Type:** Unknown (21)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ValueName` | B-Tree | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ValueName`
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:37Z*
