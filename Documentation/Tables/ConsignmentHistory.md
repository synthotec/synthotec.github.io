---
layout : default
title : ConsignmentHistory
parent : Tables
---
# ConsignmentHistory

📊 **Overview:** 6 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 73
- **UUID:** C0E7A8FCF0E83E42B41416BAD0691019
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:10Z

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
| UsageDate | `Integer` | 🚫 Not Null | - |
| FromDate | `Integer` | 🚫 Not Null | - |
| Quantity | `Date` | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### UsageDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### FromDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Customer

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
*Generated at: 2025-11-13T02:36:10Z*
