---
layout : default
title : Staff
parent : Classes
---
# Staff [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Staff.4dm)

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T16:35:59.415Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [getUsingKeyfob](#getusingkeyfob) (2 params) → `$StaffEntity : cs.StaffEntity` 🖥️
  - [getCurrentUser](#getcurrentuser) → `cs.StaffEntity` 🖥️
  - [getNonArchived](#getnonarchived) → `cs.StaffSelection` 🖥️
  - [newUsingEntry](#newusingentry) → `cs.StaffEntity` 🖥️
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### getUsingKeyfob {#getusingkeyfob}
 `[🖥️ local]`

```4d
Function getUsingKeyfob($ShowWarning : Boolean; $KeyFob : Text) -> $StaffEntity : cs.StaffEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ShowWarning` | `Boolean` | - | - |
| `$KeyFob` | `Text` | - | - |

**Returns:** `cs.StaffEntity`

---

#### getCurrentUser {#getcurrentuser}
 `[🖥️ local]`

```4d
Function getCurrentUser -> cs.StaffEntity
```

**Returns:** `cs.StaffEntity`

---

#### getNonArchived {#getnonarchived}
 `[🖥️ local]`

```4d
Function getNonArchived -> cs.StaffSelection
```

**Returns:** `cs.StaffSelection`

---

#### newUsingEntry {#newusingentry}
 `[🖥️ local]`

```4d
Function newUsingEntry -> cs.StaffEntity
```

**Returns:** `cs.StaffEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Staff](../Tables/Staff.md) - Source table for this ORDA class

### � Related Classes

- [StaffEntity](StaffEntity.md) - ORDA Entity class for Staff table

---

*Generated from Staff.4dm*
