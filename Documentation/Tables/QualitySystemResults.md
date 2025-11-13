---
layout : default
title : QualitySystemResults
parent : Tables
---
# QualitySystemResults

📊 **Overview:** 22 Fields | 4 Indexes

## ℹ️ Table Information

- **Table ID:** 99
- **UUID:** C46FD557FC0E4A4E995DC54102D0087E
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:33Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (22)
- [🔍 Indexes](#-indexes) (4)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| System | `String` (255) | 🚫 Not Null | - |
| Procedure | `String` (255) | 🚫 Not Null | - |
| Subject | `String` (255) | 🚫 Not Null | - |
| Result | `Boolean` | 🚫 Not Null | - |
| TargetMin | `Boolean` | 🚫 Not Null | - |
| TargetMax | `Boolean` | 🚫 Not Null | - |
| Completed | `Real` | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |
| CompletedDate | `Integer` | 🚫 Not Null | - |
| CompletedTime | `Long Integer` | 🚫 Not Null | - |
| AdditionalDetail | `String` (255) | 🚫 Not Null | - |
| Comment | `String` (255) | 🚫 Not Null | - |
| ResultPassStatus | `Real` | 🚫 Not Null | - |
| AdditionalID | `Date` | 🚫 Not Null | - |
| SubjectID | `Date` | 🚫 Not Null | - |
| Confirmed | `Real` | 🚫 Not Null | - |
| ConfirmedDate | `Integer` | 🚫 Not Null | - |
| ConfirmedTime | `Long Integer` | 🚫 Not Null | - |
| ConfirmedBy | `String` (255) | 🚫 Not Null | - |
| ProcedureOrder | `Picture` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### System

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Procedure

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Subject

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Result

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TargetMin

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TargetMax

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Completed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CompletedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CompletedDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CompletedTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### AdditionalDetail

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Comment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ResultPassStatus

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AdditionalID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SubjectID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Confirmed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ConfirmedDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ConfirmedTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### ConfirmedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ProcedureOrder

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Completed` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `System` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Completed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `System`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:33Z*
