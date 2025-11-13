---
layout : default
title : WorkRequestComments
parent : Tables
---
# WorkRequestComments

📊 **Overview:** 8 Fields | 1 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 66
- **UUID:** 17EBB00DC2A338479A5DE717852AEA8A
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:03Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| WorkRequestID | `Date` | 🚫 Not Null | - |
| Comment | `String` | 🚫 Not Null | - |
| CommentBy | `String` (255) | 🚫 Not Null | - |
| CommentDate | `Integer` | 🚫 Not Null | - |
| Public | `Real` | 🚫 Not Null | - |
| CommentTime | `String` (255) | 🚫 Not Null | - |
| StaffID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### WorkRequestID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Comment

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### CommentBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CommentDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Public

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CommentTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### StaffID

**Properties:**

- **Type:** Date

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

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorkRequestsEntity` | [WorkRequests](WorkRequests.md) | `WorkRequestID` → `ID` | Active |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active |

### Detailed Information

#### WorkRequestsEntity

**Links to:** [WorkRequests](WorkRequests.md)

- **Source Field:** `WorkRequestID`
- **Destination Field:** `ID`
- **State:** Active

---

#### StaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:03Z*
