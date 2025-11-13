---
layout : default
title : Permissions
parent : Classes
---
# Permissions

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T23:17:38.621Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [getByName](#getbyname) (1 param) → `$PermissionsEntity : cs.PermissionsEntity`
- [check](#check) (3 params) → `$HasPermission : Boolean` 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

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

- [Permissions](../Tables/Permissions.md) - Source table for this ORDA class

### � Related Classes

- [PermissionsEntity](PermissionsEntity.md) - ORDA Entity class for Permissions table

---

*Generated from Permissions.4dm*
