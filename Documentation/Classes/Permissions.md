---
layout : default
title : Permissions
parent : Classes
---
# Permissions

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T14:26:50.346Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [getByName](#getbyname) (1 param) → `$PermissionsEntity : cs.PermissionsEntity`
- [check](#check) (3 params) → `$HasPermission : Boolean` 🖥️

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

---

*Generated from Permissions.4dm*
