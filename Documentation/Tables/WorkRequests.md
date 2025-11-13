---
layout : default
title : WorkRequests
parent : Tables
---
# WorkRequests

📊 **Overview:** 18 Fields | 4 Indexes | 1 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 65
- **UUID:** F442B2C4FB8A82459B54D0CF985365AB
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:02Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| CreatedDate | `Integer` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| FaultLocation | `String` (255) | 🚫 Not Null | - |
| UnitNumber | `Picture` | 🚫 Not Null | - |
| Priority | `String` (255) | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |
| CorrectiveAction | `String` (255) | 🚫 Not Null | - |
| TargetDate | `Integer` | 🚫 Not Null | - |
| Cost | `Boolean` | 🚫 Not Null | - |
| Completed | `Real` | 🚫 Not Null | - |
| CompletedDate | `Integer` | 🚫 Not Null | - |
| Category | `String` (255) | 🚫 Not Null | - |
| LastComment | `String` (255) | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |
| LastCommentTime | `String` (255) | 🚫 Not Null | - |
| ToolNo | `String` (255) | 🚫 Not Null | - |
| ToolID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### CreatedDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CreatedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FaultLocation

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### UnitNumber

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Priority

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Description

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CorrectiveAction

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### TargetDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Cost

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Completed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CompletedDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Category

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### LastComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CompletedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### LastCommentTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolNo

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolNo` | Keywords | regular | - |
| `Category` | Keywords | regular | - |
| `Completed` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ToolNo`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Category`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Completed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `WorkRequestCommentsSelection` | [WorkRequestComments](WorkRequestComments.md) | `WorkRequestID` → `ID` | Active |
| `ToolMaintenanceLogSelection` | [ToolMaintenanceLog](ToolMaintenanceLog.md) | `WorkRequestID` → `ID` | Active |

### Detailed Information

#### WorkRequestCommentsSelection

**Links from:** [WorkRequestComments](WorkRequestComments.md)

- **Source Table:** `WorkRequestComments`
- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

#### ToolMaintenanceLogSelection

**Links from:** [ToolMaintenanceLog](ToolMaintenanceLog.md)

- **Source Table:** `ToolMaintenanceLog`
- **Source Field:** `WorkRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:02Z*
