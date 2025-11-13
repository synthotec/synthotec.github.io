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
- **Generated:** 🕐 2025-11-13T16:09:23Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `String` | 🔑 PK, ✨ Unique | - |
| ToolID | `Date` | 🚫 Not Null | - |
| MaintenanceDate | `Integer` | 🚫 Not Null | - |
| MaintenanceTime | `Long Integer` | 🚫 Not Null | - |
| MaintenanceWho | `String` (255) | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| CycleCount | `Date` | 🚫 Not Null | - |
| BypassCountReset | `Real` | 🚫 Not Null | - |
| WorkRequestID | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |
| `WorkRequestsEntity` | [WorkRequests](WorkRequests.md) | `WorkRequestID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:09:23Z*
