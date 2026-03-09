---
layout : default
title : Settings
parent : Classes
---
# Settings [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Settings.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

DataClass for application settings records, providing get-or-create access for both global settings (no staff ID) and per-staff settings. Used throughout the system to persist configuration values of any type.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.558Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
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

Gets or creates a global setting by variable name (StaffID is null for global settings)

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

Gets or creates a user-specific setting by variable name and staff ID

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$VariableName` | `Text` | - | - |
| `$StaffID` | `Integer` | - | - |

**Returns:** `cs.SettingsEntity`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Settings](../Tables/Settings.md) - ORDA DataClass class for Settings table

### � Related Classes

- [SettingsEntity](SettingsEntity.md) - ORDA Entity class for Settings table

### � Forms

- [%2AMethodList](../Forms/%2AMethodList.md) - Data source for %2AMethodList form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [LabelHistory](../Forms/LabelHistory.md) - Data source for LabelHistory form
- [LocationManager](../Forms/LocationManager.md) - Data source for LocationManager form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [ProcurementProgramImporter](../Forms/ProcurementProgramImporter.md) - Data source for ProcurementProgramImporter form
- [Schedule_Variables](../Forms/Schedule_Variables.md) - Data source for Schedule_Variables form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from Settings.4dm*
