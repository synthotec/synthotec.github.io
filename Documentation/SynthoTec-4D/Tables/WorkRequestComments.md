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
- **Generated:** 🕐 2025-11-13T23:18:43Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (2)

---

## 📋 Fields

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

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorkRequestsEntity` | [WorkRequests](WorkRequests.md) | `WorkRequestID` → `ID` | Active | - |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [AddWorkRequest](../Forms/AddWorkRequest.md) - Data source for AddWorkRequest form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:43Z*
