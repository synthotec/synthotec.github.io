---
layout : default
title : Error
parent : Tables
---
# Error

📊 **Overview:** 7 Fields | 2 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 131
- **UUID:** AF1DEE5EA76ACE42AEFB98922A785EEB
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:22Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| Code | `Date` | - | - |
| Method | `String` (255) | - | - |
| Line | `Date` | - | - |
| Formula | `String` (255) | - | - |
| GithubIssue | `Unknown (21)` | - | - |
| Suppress | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** String
- **Constraints:** 🔑 Primary Key, ✨ Unique

---

#### Code

**Properties:**

- **Type:** Date

---

#### Method

**Properties:**

- **Type:** String (max length: 255)

---

#### Line

**Properties:**

- **Type:** Date

---

#### Formula

**Properties:**

- **Type:** String (max length: 255)

---

#### GithubIssue

**Properties:**

- **Type:** Unknown (21)

---

#### Suppress

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Suppress` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Suppress`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ErrorDetailSelection` | [ErrorDetail](ErrorDetail.md) | `ErrorID` → `ID` | Active |

### Detailed Information

#### ErrorDetailSelection

**Links from:** [ErrorDetail](ErrorDetail.md)

- **Source Table:** `ErrorDetail`
- **Source Field:** `ErrorID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:37:22Z*
