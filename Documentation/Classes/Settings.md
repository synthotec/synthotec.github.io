---
layout : default
title : Settings
parent : Classes
---
# Settings

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T12:58:34.613Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (2):**

- [global](#global) (1 param) → `cs.SettingsEntity` 🖥️
- [userSpecific](#userspecific) (2 params) → `cs.SettingsEntity` 🖥️

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### global {#global}
 `[🖥️ local]`

```4d
Function global($VariableName : Text) -> cs.SettingsEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$VariableName` | `Text` | - | - |

**Returns:** `cs.SettingsEntity`

---

#### userSpecific {#userspecific}
 `[🖥️ local]`

```4d
Function userSpecific($VariableName : Text; $StaffID : Integer) -> cs.SettingsEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$VariableName` | `Text` | - | - |
| `$StaffID` | `Integer` | - | - |

**Returns:** `cs.SettingsEntity`

---

## 🔗 Related Items

### 📦 Related Classes

- [Settings](Settings.md) - DataClass class
- [SettingsEntity](SettingsEntity.md) - Entity class

### 🗂️ Used By Tables

- [Settings](../Tables/Settings.md) - DataClass class

---

*Generated from Settings.4dm*
