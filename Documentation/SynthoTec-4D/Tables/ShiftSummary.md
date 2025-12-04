---
layout : default
title : ShiftSummary
parent : Tables
---
# ShiftSummary

📊 **Overview:** 6 Fields | 3 Indexes | 1 Many-to-One Relations | 1 One-to-Many Relations

## 📝 Description

🗨️ Summary table aggregating production performance by shift. Provides high-level metrics for output, downtime, and efficiency per shift.

## ℹ️ Table Information

- **Table ID:** 129
- **UUID:** 9F8A3252F6D9E74589B429EA78C73E40
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:28Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Date | `Date` | - | - |
| Time | `Time` | - | - |
| StaffID | `Long Integer` | - | - |
| Commentary | `String` | - | - |
| EmailSent | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `StaffID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Date` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ShiftSummaryDetailSelection` | [ShiftSummaryDetail](ShiftSummaryDetail.md) | `ShiftSummaryID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ShiftSummaryEntity](../Classes/ShiftSummaryEntity.md) - ORDA Entity class for ShiftSummary table

### 📄 Forms

- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:28Z*
