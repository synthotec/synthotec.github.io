---
layout : default
title : Staff
parent : Tables
---
# Staff

📊 **Overview:** 20 Fields | 1 Indexes | 10 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 42
- **UUID:** 34740841F2B0904CA92D155632F47E87
- **Primary Key:** 🔑 `StaffID`
- **Generated:** 🕐 2025-11-13T16:08:26Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (20)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (10)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Email | `String` (255) | 🚫 Not Null | - |
| FirstName | `String` (255) | 🚫 Not Null | - |
| LastName | `String` (255) | 🚫 Not Null | - |
| PrintAs | `String` (255) | 🚫 Not Null | - |
| FobID | `String` (255) | 🚫 Not Null | - |
| AccountAD | `String` (255) | 🚫 Not Null | - |
| SelfApprovalLimit | `Boolean` | 🚫 Not Null | - |
| WorkRequestEmail | `String` (255) | - | - |
| Account4D | `String` (255) | 🚫 Not Null | - |
| SharedAccount | `Real` | 🚫 Not Null | - |
| Code | `String` (255) | 🚫 Not Null | - |
| 🔑 **StaffID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Stock | `Real` | 🚫 Not Null | - |
| UserID | `String` (255) | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |
| PO_Approval | `Real` | 🚫 Not Null | - |
| Mobile | `String` (255) | 🚫 Not Null | - |
| PasswordHash | `String` (255) | 🚫 Not Null | - |
| PersonalEmail | `String` (255) | 🚫 Not Null | - |
| MobileKeyfob | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `StaffID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `StaffPermissionsSelection` | [StaffPermissions](StaffPermissions.md) | `StaffID` → `StaffID` | Active | - |
| `DB_VariablesSelection` | [Settings](Settings.md) | `StaffID` → `StaffID` | Active | - |
| `WorkRequestCommentsSelection` | [WorkRequestComments](WorkRequestComments.md) | `StaffID` → `StaffID` | Active | - |
| `RealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `StaffID` → `StaffID` | Active | - |
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `StaffID` → `StaffID` | Active | - |
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `StaffID` → `StaffID` | Active | - |
| `ShiftSummarySelection` | [ShiftSummary](ShiftSummary.md) | `StaffID` → `StaffID` | Active | - |
| `StatusUpdatedBoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `StatusUpdatedStaffID` → `StaffID` | Active | - |
| `ToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `StaffID` → `StaffID` | Active | - |
| `DeactivatedToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `DeactivatedStaffID` → `StaffID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Staff](../Classes/Staff.md) - ORDA DataClass class for Staff table
- [StaffEntity](../Classes/StaffEntity.md) - ORDA Entity class for Staff table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:26Z*
