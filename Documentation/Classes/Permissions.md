---
layout : default
title : Permissions
parent : Classes
---
# Permissions

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T16:35:14.944Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [getByName](#getbyname) (1 param) → `$PermissionsEntity : cs.PermissionsEntity`
- [check](#check) (3 params) → `$HasPermission : Boolean` 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (1)

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

## 🔗 Related Items

### 🗂️ Tables

- [Permissions](../Tables/Permissions.md) - Source table

---

*Generated from Permissions.4dm*
