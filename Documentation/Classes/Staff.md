---
layout : default
title : Staff
parent : Classes
---
# Staff

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T12:58:34.649Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (4):**

- [getUsingKeyfob](#getusingkeyfob) (2 params) → `cs.StaffEntity` 🖥️
- [getCurrentUser](#getcurrentuser) → `cs.StaffEntity` 🖥️
- [getNonArchived](#getnonarchived) → `cs.StaffSelection` 🖥️
- [newUsingEntry](#newusingentry) → `cs.StaffEntity` 🖥️

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getUsingKeyfob {#getusingkeyfob}
 `[🖥️ local]`

```4d
Function getUsingKeyfob($ShowWarning : Boolean; $KeyFob : Text) -> cs.StaffEntity
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

## 🔗 Related Items

### 📦 Related Classes

- [Staff](Staff.md) - DataClass class
- [StaffEntity](StaffEntity.md) - Entity class

### 📄 Forms

- [Staff](../Forms/Staff.md) - DataClass class

---

*Generated from Staff.4dm*
