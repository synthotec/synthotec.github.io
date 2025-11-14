---
layout : default
title : Settings
parent : Classes
---
# Settings [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Settings.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T00:07:28.869Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [global](#global) (1 param) → `$SettingsEntity : cs.SettingsEntity` 🖥️
  - [userSpecific](#userspecific) (2 params) → `$SettingsEntity : cs.SettingsEntity` 🖥️
- [🔗 Related Items](#related-items)
---

## Functions {#functions}

### Regular Functions

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

## Related Items {#related-items}

### 🗂️ Tables

- [Settings](../Tables/Settings.md) - Source table for this ORDA class

### � Related Classes

- [SettingsEntity](SettingsEntity.md) - ORDA Entity class for Settings table

---

*Generated from Settings.4dm*
