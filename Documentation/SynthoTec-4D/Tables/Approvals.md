---
layout : default
title : Approvals
parent : Tables
---
# Approvals

📊 **Overview:** 13 Fields | 2 Indexes | 2 Many-to-One Relations

## 📝 Description

🗨️ Workflow table tracking approval requests and decisions for product changes, tool modifications, and quality exceptions. Links to Product, Tools, and Staff.

## ℹ️ Table Information

- **Table ID:** 62
- **UUID:** 6588D29DE7A2FE44BEEA0304F247C2A0
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:24Z

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
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Long Integer` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| FullApproval | `Boolean` | 🚫 Not Null | - |
| ApprovalType | `String` (255) | 🚫 Not Null | - |
| ConditionalApproval | `Boolean` | 🚫 Not Null | - |
| ConditionalUntil | `Date` | 🚫 Not Null | - |
| Issue | `String` (255) | 🚫 Not Null | - |
| BypassApproval | `Boolean` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| ApprovedBy | `String` (255) | 🚫 Not Null | - |
| ApprovedWhen | `Date` | 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

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

- [Approvals](../Classes/Approvals.md) - ORDA DataClass class for Approvals table
- [ApprovalsEntity](../Classes/ApprovalsEntity.md) - ORDA Entity class for Approvals table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:24Z*
