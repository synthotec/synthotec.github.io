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
- **Generated:** 🕐 2025-11-13T23:18:42Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

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

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolNo` | Keywords | regular | - |
| `Category` | Keywords | regular | - |
| `Completed` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `WorkRequestCommentsSelection` | [WorkRequestComments](WorkRequestComments.md) | `WorkRequestID` → `ID` | Active | - |
| `ToolMaintenanceLogSelection` | [ToolMaintenanceLog](ToolMaintenanceLog.md) | `WorkRequestID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:42Z*
