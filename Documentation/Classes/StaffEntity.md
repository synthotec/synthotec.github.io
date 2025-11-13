---
layout : default
title : StaffEntity
parent : Classes
---
# StaffEntity

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T13:33:27.493Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [permissionCheck](#permissioncheck) (2 params) → `Boolean` 🖥️
- [copyPermissionsFrom](#copypermissionsfrom) (1 param) → `Boolean` 🖥️

**🔍 Getters (1):**

- [FullName](#fullname) → `Text`

### 🔗 Related Items

- [Tables](#-tables) (1)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### permissionCheck {#permissioncheck}
 `[🖥️ local]`

```4d
Function permissionCheck($PermissionName : Text; $DisplayWarning : Boolean) -> Boolean
```

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
Function copyPermissionsFrom($StaffEntity : cs.StaffEntity) -> Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StaffEntity` | `cs.StaffEntity` | - | - |

**Returns:** `Boolean`

---

### 🔍 Getters

#### FullName {#fullname}
 `[🖥️ local, 🔍 getter]`

```4d
Function FullName -> Text
```

**Returns:** `Text`

---

## 🔗 Related Items

### 🗂️ Tables

- [Staff](../Tables/Staff.md) - Entity class

---

*Generated from StaffEntity.4dm*
