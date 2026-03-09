---
layout : default
title : StaffEntity
parent : Classes
---
# StaffEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/StaffEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

## 📝 Description

Entity representing a system user / staff member, with a full name helper, a permission check method with optional warning display, and an alias mapping the primary key to StaffID.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:31.635Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [permissionCheck](#permissioncheck) (2 params) → `$HasPermission : Boolean` 🖥️
    - [copyPermissionsFrom](#copypermissionsfrom) (1 param) → `$Success : Boolean` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [FullName](#fullname) 🔍 → `Text`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### permissionCheck {#permissioncheck}
 `[🖥️ local]`

```4d
Function permissionCheck($PermissionName : Text; $DisplayWarning : Boolean) -> $HasPermission : Boolean
```

Checks if this staff member has the specified permission; optionally displays a warning if denied

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PermissionName` | `Text` | - | - |
| `$DisplayWarning` | `Boolean` | - | - |

**Returns:** `Boolean`

---

#### copyPermissionsFrom {#copypermissionsfrom}
 `[🖥️ local]`

```4d
Function copyPermissionsFrom($StaffEntity : cs.StaffEntity) -> $Success : Boolean
```

Copies all permissions from another staff member to this staff member within a transaction

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StaffEntity` | `cs.StaffEntity` | - | - |

**Returns:** `Boolean`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### FullName {#fullname}
 `[🔍 get only, 🖥️ local]`

```4d
Function get FullName -> Text
```

Returns the full name of the staff member by combining first and last names

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Staff](../Tables/Staff.md) - ORDA Entity class for Staff table

### � Related Classes

- [Staff](Staff.md) - ORDA DataClass class for Staff table

### � Forms

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
- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form

---

*Generated from StaffEntity.4dm*
