---
layout : default
title : SettingsEntity
parent : Classes
---
# SettingsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/SettingsEntity.4dm)

📊 **Overview:** 5 Functions

## 📝 Description

Entity representing a key-value application setting, with automatic type detection for reading and writing values of any 4D type (text, number, boolean, date, time, object). Provides a typed getValue helper with a default fallback.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:31.570Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setValue](#setvalue) (1 param) → `Boolean` 🖥️
    - [setObject](#setobject) (1 param) → `Boolean` 🖥️
    - [getValue](#getvalue) (1 param) → `Variant` 🖥️
    - [getObject](#getobject) (1 param) → `Object` 🖥️
    - [reset](#reset) → `Boolean` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### setValue {#setvalue}
 `[🖥️ local]`

```4d
Function setValue($Value : Variant) -> Boolean
```

Sets the setting value with automatic type detection and storage

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Value` | `Variant` | - | - |

**Returns:** `Boolean`

---

#### setObject {#setobject}
 `[🖥️ local]`

```4d
Function setObject($Object : Object) -> Boolean
```

Sets the setting value as an object directly

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Object` | `Object` | - | - |

**Returns:** `Boolean`

---

#### getValue {#getvalue}
 `[🖥️ local]`

```4d
Function getValue($DefaultValue : Variant) -> Variant
```

Gets the stored value, using default value if not set

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DefaultValue` | `Variant` | - | - |

**Returns:** `Variant`

---

#### getObject {#getobject}
 `[🖥️ local]`

```4d
Function getObject($DefaultValue : Variant) -> Object
```

Gets the stored object, using default value if not set

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DefaultValue` | `Variant` | - | - |

**Returns:** `Object`

---

#### reset {#reset}
 `[🖥️ local]`

```4d
Function reset -> Boolean
```

Clears the setting value by setting Object to null

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Settings](../Tables/Settings.md) - ORDA Entity class for Settings table

### � Related Classes

- [Settings](Settings.md) - ORDA DataClass class for Settings table

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

*Generated from SettingsEntity.4dm*
