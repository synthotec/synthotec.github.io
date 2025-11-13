---
layout : default
title : CompanyNotices
parent : Tables
---
# CompanyNotices

📊 **Overview:** 11 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 61
- **UUID:** 015540DC6D91DB4182E6B439B2252CC2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:59Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Category | `String` (255) | 🚫 Not Null | - |
| Title | `String` (255) | 🚫 Not Null | - |
| Description | `String` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| ShowDuration | `Picture` | 🚫 Not Null | - |
| Image | `Picture` | 🚫 Not Null | - |
| Colour | `Date` | 🚫 Not Null | - |
| ShowFrom | `Integer` | 🚫 Not Null | - |
| ShowUntil | `Integer` | 🚫 Not Null | - |
| Archived | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Category

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Title

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Description

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### CreatedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ShowDuration

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Image

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Colour

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ShowFrom

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ShowUntil

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Archived

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Archived` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Archived`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:59Z*
