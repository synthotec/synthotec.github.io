---
layout : default
title : Settings
parent : Classes
---
# Settings

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T16:13:51.230Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [global](#global) (1 param) → `$SettingsEntity : cs.SettingsEntity` 🖥️
- [userSpecific](#userspecific) (2 params) → `$SettingsEntity : cs.SettingsEntity` 🖥️

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### global {#global}
 `[🖥️ local]`

```4d
Function global($VariableName : Text) -> $SettingsEntity : cs.SettingsEntity
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
Function userSpecific($VariableName : Text; $StaffID : Integer) -> $SettingsEntity : cs.SettingsEntity
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$VariableName` | `Text` | - | - |
| `$StaffID` | `Integer` | - | - |

**Returns:** `cs.SettingsEntity`

---

---

*Generated from Settings.4dm*
