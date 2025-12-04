---
layout : default
title : Permissions
parent : Tables
---
# Permissions

📊 **Overview:** 2 Fields | 1 Indexes | 1 One-to-Many Relations

## 📝 Description

🗨️ Security lookup table defining system permissions and access rights. Used to control user capabilities and feature access by role.

## ℹ️ Table Information

- **Table ID:** 87
- **UUID:** E8C07233B3BC574991307875E3D2E16F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (2)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (9)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `StaffPermissionsSelection` | [StaffPermissions](StaffPermissions.md) | `PermissionID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Permissions](../Classes/Permissions.md) - ORDA DataClass class for Permissions table
- [PermissionsEntity](../Classes/PermissionsEntity.md) - ORDA Entity class for Permissions table

### 📄 Forms

- [Errors](../Forms/Errors.md) - Data source for Errors form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [PermissionManager](../Forms/PermissionManager.md) - Data source for PermissionManager form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form
- [ToolDocuments](../Forms/ToolDocuments.md) - Data source for ToolDocuments form
- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form
- [Schedule_Planner](../Forms/Schedule_Planner.md) - Data source for Schedule_Planner form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:49Z*
