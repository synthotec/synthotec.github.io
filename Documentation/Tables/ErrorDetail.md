---
layout : default
title : ErrorDetail
parent : Tables
---
# ErrorDetail

📊 **Overview:** 7 Fields | 4 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 132
- **UUID:** E06316D0DEB08A45A8A203D136C74702
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:23Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ErrorID | `String` | - | - |
| Date | `Integer` | - | - |
| Time | `Long Integer` | - | - |
| ErrorObject | `Unknown (21)` | - | - |
| User | `String` (255) | - | - |
| Machine | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ErrorID

**Properties:**

- **Type:** String

---

#### Date

**Properties:**

- **Type:** Integer

---

#### Time

**Properties:**

- **Type:** Long Integer

---

#### ErrorObject

**Properties:**

- **Type:** Unknown (21)

---

#### User

**Properties:**

- **Type:** String (max length: 255)

---

#### Machine

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Date` | Keywords | regular | - |
| `ErrorID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Time` | Keywords | regular | - |

### Detailed Information

- **Field:** `Date`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ErrorID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Time`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ErrorEntity` | [Error](Error.md) | `ErrorID` → `ID` | Active |

### Detailed Information

#### ErrorEntity

**Links to:** [Error](Error.md)

- **Source Field:** `ErrorID`
- **Destination Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:37:23Z*
