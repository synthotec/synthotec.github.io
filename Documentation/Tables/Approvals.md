---
layout : default
title : Approvals
parent : Tables
---
# Approvals

📊 **Overview:** 13 Fields | 2 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 62
- **UUID:** 6588D29DE7A2FE44BEEA0304F247C2A0
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:48:36Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| FullApproval | `Real` | 🚫 Not Null | - |
| ApprovalType | `String` (255) | 🚫 Not Null | - |
| ConditionalApproval | `Real` | 🚫 Not Null | - |
| ConditionalUntil | `Integer` | 🚫 Not Null | - |
| Issue | `String` (255) | 🚫 Not Null | - |
| BypassApproval | `Real` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| ApprovedBy | `String` (255) | 🚫 Not Null | - |
| ApprovedWhen | `Integer` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Approvals](../Classes/Approvals.md) - DataClass class
- [ApprovalsEntity](../Classes/ApprovalsEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:36Z*
