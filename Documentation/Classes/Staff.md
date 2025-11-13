---
layout : default
title : Staff
parent : Classes
---
# Staff

📊 **Overview:** 4 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T16:46:52.787Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (4):**

- [getUsingKeyfob](#getusingkeyfob) (2 params) → `$StaffEntity : cs.StaffEntity` 🖥️
- [getCurrentUser](#getcurrentuser) → `cs.StaffEntity` 🖥️
- [getNonArchived](#getnonarchived) → `cs.StaffSelection` 🖥️
- [newUsingEntry](#newusingentry) → `cs.StaffEntity` 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (1)

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

## 🔗 Related Items

### 🗂️ Tables

- [Staff](../Tables/Staff.md) - Source table

---

*Generated from Staff.4dm*
