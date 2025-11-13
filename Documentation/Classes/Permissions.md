---
layout : default
title : Permissions
parent : Classes
---
# Permissions

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T13:29:03.038Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (2):**

- [getByName](#getbyname) (1 param) → `cs.PermissionsEntity`
- [check](#check) (3 params) → `Boolean` 🖥️

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getByName {#getbyname}


```4d
Function getByName($PermissionName : Text) -> cs.PermissionsEntity
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
Function check($PermissionName : Text; $DisplayWarning : Boolean; $StaffEntity : cs.StaffEntity) -> Boolean
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
