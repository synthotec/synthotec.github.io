---
layout : default
title : SettingsEntity
parent : Classes
---
# SettingsEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/SettingsEntity.4dm)

📊 **Overview:** 5 Functions

**Extends:** `Entity`

🕐 *Last updated: 2025-12-10T11:45:24.299Z*

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
