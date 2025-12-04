---
layout : default
title : ToolMaintenanceLog
parent : Tables
---
# ToolMaintenanceLog

📊 **Overview:** 9 Fields | 1 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 105
- **UUID:** 1F02089890EA3F489FED75E8E2877B11
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| ToolID | `Long Integer` | 🚫 Not Null | - |
| MaintenanceDate | `Date` | 🚫 Not Null | - |
| MaintenanceTime | `Time` | 🚫 Not Null | - |
| MaintenanceWho | `String` (255) | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| CycleCount | `Long Integer` | 🚫 Not Null | - |
| BypassCountReset | `Boolean` | 🚫 Not Null | - |
| WorkRequestID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |
| `WorkRequestsEntity` | [WorkRequests](WorkRequests.md) | `WorkRequestID` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [ToolMaintenanceLog](../Forms/ToolMaintenanceLog.md) - Data source for ToolMaintenanceLog form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:49Z*
