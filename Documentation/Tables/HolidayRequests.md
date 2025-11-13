---
layout : default
title : HolidayRequests
parent : Tables
---
# HolidayRequests

📊 **Overview:** 7 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 79
- **UUID:** 26B56558930CE9449F07B020C86BEA93
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:15Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StaffName | `String` (255) | 🚫 Not Null | - |
| FirstDate | `Integer` | 🚫 Not Null | - |
| LastDate | `Integer` | 🚫 Not Null | - |
| Days | `Boolean` | 🚫 Not Null | - |
| Comment | `String` (255) | 🚫 Not Null | - |
| Status | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### StaffName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FirstDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### LastDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Days

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Comment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Status

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Status` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Status`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:15Z*
