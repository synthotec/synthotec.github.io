---
layout : default
title : Permissions
parent : Classes
---
# Permissions [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Permissions.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T16:53:00.943Z*

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

- [Permissions](../Tables/Permissions.md) - Source table for this ORDA class

### � Related Classes

- [PermissionsEntity](PermissionsEntity.md) - ORDA Entity class for Permissions table

---

*Generated from Permissions.4dm*
