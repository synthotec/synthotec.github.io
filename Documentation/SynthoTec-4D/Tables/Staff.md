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
- **Generated:** 🕐 2025-12-03T16:23:52Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (20)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (10)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (15)

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
| SelfApprovalLimit | `Real` | 🚫 Not Null | - |
| WorkRequestEmail | `String` (255) | - | - |
| Account4D | `String` (255) | 🚫 Not Null | - |
| SharedAccount | `Boolean` | 🚫 Not Null | - |
| Code | `String` (255) | 🚫 Not Null | - |
| 🔑 **StaffID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Stock | `Boolean` | 🚫 Not Null | - |
| UserID | `String` (255) | 🚫 Not Null | - |
| Archive | `Boolean` | 🚫 Not Null | - |
| PO_Approval | `Boolean` | 🚫 Not Null | - |
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

### 📄 Forms

- [AddWorkRequest](../Forms/AddWorkRequest.md) - Data source for AddWorkRequest form
- [ConfirmOrderDates](../Forms/ConfirmOrderDates.md) - Data source for ConfirmOrderDates form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [PermissionManager](../Forms/PermissionManager.md) - Data source for PermissionManager form
- [PurchaseOrders](../Forms/PurchaseOrders.md) - Data source for PurchaseOrders form
- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form
- [Staff](../Forms/Staff.md) - Data source for Staff form
- [StaffLogin](../Forms/StaffLogin.md) - Data source for StaffLogin form
- [StaffMessaging](../Forms/StaffMessaging.md) - Data source for StaffMessaging form
- [ToolMaintenanceLog](../Forms/ToolMaintenanceLog.md) - Data source for ToolMaintenanceLog form
- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:52Z*
