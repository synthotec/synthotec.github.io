---
layout : default
title : StaffEntity
parent : Classes
---
# StaffEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/StaffEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T15:47:09.916Z*

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

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### FullName {#fullname}
 `[🔍 get only, 🖥️ local]`

```4d
Function get FullName -> Text
```

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Staff](../Tables/Staff.md) - Source table for this ORDA class

---

*Generated from StaffEntity.4dm*
