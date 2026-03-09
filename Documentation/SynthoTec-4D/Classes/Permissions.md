---
layout : default
title : Permissions
parent : Classes
---
# Permissions [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Permissions.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

DataClass for application permission records, providing get-or-create access by permission name. Used throughout the system to define and check role-based access control rules for staff.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.360Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getByName](#getbyname) (1 param) → `$PermissionsEntity : cs.PermissionsEntity`
    - [check](#check) (3 params) → `$HasPermission : Boolean` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getByName {#getbyname}


```4d
Function getByName($PermissionName : Text) -> $PermissionsEntity : cs.PermissionsEntity
```

Gets or creates a permission by name

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PermissionName` | `Text` | - | - |

**Returns:** `cs.PermissionsEntity`

---

#### check {#check}
 `[🖥️ local]`

```4d
Function check($PermissionName : Text; $DisplayWarning : Boolean; $StaffEntity : cs.StaffEntity) -> $HasPermission : Boolean
```

Checks if a staff member has a specific permission and optionally displays a warning if denied

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PermissionName` | `Text` | - | - |
| `$DisplayWarning` | `Boolean` | - | - |
| `$StaffEntity` | `cs.StaffEntity` | - | - |

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Permissions](../Tables/Permissions.md) - ORDA DataClass class for Permissions table

### � Related Classes

- [PermissionsEntity](PermissionsEntity.md) - ORDA Entity class for Permissions table

### � Forms

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

*Generated from Permissions.4dm*
