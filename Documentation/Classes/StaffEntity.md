---
layout : default
title : StaffEntity
parent : Classes
---
# StaffEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/StaffEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:07:28.913Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [permissionCheck](#permissioncheck) (2 params) → `$HasPermission : Boolean` 🖥️
  - [copyPermissionsFrom](#copypermissionsfrom) (1 param) → `$Success : Boolean` 🖥️
  - [FullName](#fullname) → `Text`
- [🔗 Related Items](#related-items)
---

## Functions {#functions}

### Regular Functions

#### permissionCheck {#permissioncheck}
 `[🖥️ local]`

```4d
Function permissionCheck($PermissionName : Text; $DisplayWarning : Boolean) -> $HasPermission : Boolean
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
Function copyPermissionsFrom($StaffEntity : cs.StaffEntity) -> $Success : Boolean
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StaffEntity` | `cs.StaffEntity` | - | - |

**Returns:** `Boolean`

---

### Getters

#### FullName {#fullname}
 `[🖥️ local, 🔍 getter]`

```4d
Function FullName -> Text
```

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Staff](../Tables/Staff.md) - Source table for this ORDA class

### � Related Classes

- [Staff](Staff.md) - ORDA DataClass class for Staff table

---

*Generated from StaffEntity.4dm*
