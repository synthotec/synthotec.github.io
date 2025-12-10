---
layout : default
title : PermissionsEntity
parent : Classes
---
# PermissionsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PermissionsEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-12-10T11:45:23.576Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getStaffPermissionsEntity](#getstaffpermissionsentity) (1 param) → `$StaffPermissionsEntity : cs.StaffPermissionsEntity` 🖥️
    - [displayWarning](#displaywarning) (1 param) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getStaffPermissionsEntity {#getstaffpermissionsentity}
 `[🖥️ local]`

```4d
Function getStaffPermissionsEntity($StaffEntity : cs.StaffEntity) -> $StaffPermissionsEntity : cs.StaffPermissionsEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StaffEntity` | `cs.StaffEntity` | - | - |

**Returns:** `cs.StaffPermissionsEntity`

---

#### displayWarning {#displaywarning}
 `[🖥️ local]`

```4d
Function displayWarning($StaffEntity : cs.StaffEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StaffEntity` | `cs.StaffEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [Permissions](../Tables/Permissions.md) - ORDA Entity class for Permissions table

### � Related Classes

- [Permissions](Permissions.md) - ORDA DataClass class for Permissions table

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

*Generated from PermissionsEntity.4dm*
