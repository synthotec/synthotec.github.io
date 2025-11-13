---
layout : default
title : Settings
parent : Classes
---
# Settings

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T23:17:39.055Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [global](#global) (1 param) → `$SettingsEntity : cs.SettingsEntity` 🖥️
- [userSpecific](#userspecific) (2 params) → `$SettingsEntity : cs.SettingsEntity` 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

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

## 🔗 Related Items

### 🗂️ Tables

- [Settings](../Tables/Settings.md) - Source table for this ORDA class

### � Related Classes

- [SettingsEntity](SettingsEntity.md) - ORDA Entity class for Settings table

---

*Generated from Settings.4dm*
