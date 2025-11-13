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
- **Generated:** 🕐 2025-11-13T02:35:30Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (20)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (10)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### Email

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FirstName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### LastName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PrintAs

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FobID

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### AccountAD

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### SelfApprovalLimit

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### WorkRequestEmail

**Properties:**

- **Type:** String (max length: 255)

---

#### Account4D

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### SharedAccount

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Code

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### 🔑 StaffID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### Stock

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### UserID

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Archive

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### PO_Approval

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Mobile

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PasswordHash

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PersonalEmail

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MobileKeyfob

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `StaffID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `StaffID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `StaffPermissionsSelection` | [StaffPermissions](StaffPermissions.md) | `StaffID` → `StaffID` | Active |
| `DB_VariablesSelection` | [Settings](Settings.md) | `StaffID` → `StaffID` | Active |
| `WorkRequestCommentsSelection` | [WorkRequestComments](WorkRequestComments.md) | `StaffID` → `StaffID` | Active |
| `RealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `StaffID` → `StaffID` | Active |
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `StaffID` → `StaffID` | Active |
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `StaffID` → `StaffID` | Active |
| `ShiftSummarySelection` | [ShiftSummary](ShiftSummary.md) | `StaffID` → `StaffID` | Active |
| `StatusUpdatedBoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `StatusUpdatedStaffID` → `StaffID` | Active |
| `ToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `StaffID` → `StaffID` | Active |
| `DeactivatedToolNoticeSelection` | [ToolNotice](ToolNotice.md) | `DeactivatedStaffID` → `StaffID` | Active |

### Detailed Information

#### StaffPermissionsSelection

**Links from:** [StaffPermissions](StaffPermissions.md)

- **Source Table:** `StaffPermissions`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### DB_VariablesSelection

**Links from:** [Settings](Settings.md)

- **Source Table:** `Settings`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### WorkRequestCommentsSelection

**Links from:** [WorkRequestComments](WorkRequestComments.md)

- **Source Table:** `WorkRequestComments`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### RealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### ToolTemperatureTargetSelection

**Links from:** [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### PrintJobSelection

**Links from:** [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### ShiftSummarySelection

**Links from:** [ShiftSummary](ShiftSummary.md)

- **Source Table:** `ShiftSummary`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### StatusUpdatedBoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `StatusUpdatedStaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### ToolNoticeSelection

**Links from:** [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `StaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

#### DeactivatedToolNoticeSelection

**Links from:** [ToolNotice](ToolNotice.md)

- **Source Table:** `ToolNotice`
- **Source Field:** `DeactivatedStaffID`
- **This Table Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:30Z*
