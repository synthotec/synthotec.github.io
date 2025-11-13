---
layout : default
title : ShiftSummary
parent : Tables
---
# ShiftSummary

📊 **Overview:** 6 Fields | 3 Indexes | 1 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 129
- **UUID:** 9F8A3252F6D9E74589B429EA78C73E40
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:21Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Date | `Integer` | - | - |
| Time | `Long Integer` | - | - |
| StaffID | `Date` | - | - |
| Commentary | `String` | - | - |
| EmailSent | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Date

**Properties:**

- **Type:** Integer

---

#### Time

**Properties:**

- **Type:** Long Integer

---

#### StaffID

**Properties:**

- **Type:** Date

---

#### Commentary

**Properties:**

- **Type:** String

---

#### EmailSent

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `StaffID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Date` | Keywords | regular | - |

### Detailed Information

- **Field:** `StaffID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Date`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active |

### Detailed Information

#### StaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ShiftSummaryDetailSelection` | [ShiftSummaryDetail](ShiftSummaryDetail.md) | `ShiftSummaryID` → `ID` | Active |

### Detailed Information

#### ShiftSummaryDetailSelection

**Links from:** [ShiftSummaryDetail](ShiftSummaryDetail.md)

- **Source Table:** `ShiftSummaryDetail`
- **Source Field:** `ShiftSummaryID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:37:21Z*
