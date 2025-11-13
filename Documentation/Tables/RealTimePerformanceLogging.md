---
layout : default
title : RealTimePerformanceLogging
parent : Tables
---
# RealTimePerformanceLogging

📊 **Overview:** 3 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 110
- **UUID:** FFD7EEFC747D6D4D857DC0F0952A3D8B
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:42Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Action | `String` (255) | 🚫 Not Null | - |
| Seconds | `Boolean` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Action

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Seconds

**Properties:**

- **Type:** Boolean
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
*Generated at: 2025-11-13T02:36:42Z*
