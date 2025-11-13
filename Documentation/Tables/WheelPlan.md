---
layout : default
title : WheelPlan
parent : Tables
---
# WheelPlan

📊 **Overview:** 4 Fields | 5 Indexes

## ℹ️ Table Information

- **Table ID:** 72
- **UUID:** 0FCA2FC5DFE22B4BBA03615CB63249A2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:09Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (5)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Machine | `Date` | 🚫 Not Null | - |
| dDate | `Integer` | 🚫 Not Null | - |
| Planned | `Boolean` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Machine

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### dDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Planned

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `dDate` | B-Tree | regular | - |
| `dDate` | Keywords | regular | - |
| `Machine` | Keywords | regular | - |
| `Machine` | B-Tree | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `dDate`
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `dDate`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine`
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:09Z*
