---
layout : default
title : ExcelXMLFileStyle
parent : Classes
---
# ExcelXMLFileStyle [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ExcelXMLFileStyle.4dm)

📊 **Overview:** 9 Properties | 1 Constructor | 4 Functions

## 📝 Description

Creates a new Excel cell style with default font settings

🕐 *Last updated: 2026-01-13T16:04:11.744Z*

---

## 📑 Table of Contents

- [📋 Properties (9)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setFontStyle](#setfontstyle) (5 params) → `cs.ExcelXMLFileStyle`
    - [setInteriorColor](#setinteriorcolor) (1 param) → `cs.ExcelXMLFileStyle`
    - [setNumberFormat](#setnumberformat) (1 param) → `cs.ExcelXMLFileStyle`
    - [setAlignment](#setalignment) (2 params) → `cs.ExcelXMLFileStyle`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `NumberFormat_ShortDate` | `Text` | `"Short Date"` | Constant for short date format |
| `NumberFormat_dd_mmm` | `Text` | `"dd\\-mmm"` | Constant for day-month format |
| `NumberFormat_Decimal` | `Text` | `"General;#;;@"` | Constant for decimal number format |
| `NumberFormat_Number` | `Text` | `"#,###,###,##0"` | Constant for integer number format with thousand separators |
| `Font` | `Object` | `{}` | Font properties (name, family, size, color, bold) |
| `Interior` | `Object` | `{}` | Cell background properties (color, pattern) |
| `Alignment` | `Object` | `{}` | Text alignment properties (horizontal, vertical) |
| `NumberFormat` | `Text` | `"General"` | Current number format for this style |
| `ID` | `Text` | - | Unique identifier for this style |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Creates a new Excel cell style with default font settings

---

## Functions {#functions}

### Regular Functions

#### setFontStyle {#setfontstyle}


```4d
Function setFontStyle($Name : Text; $Family : Text; $Size : Real; $Color : Integer; $Bold : Boolean) -> cs.ExcelXMLFileStyle
```

Sets font properties (name, family, size, color, bold) with defaults (Calibri, Swiss, 11pt, black, not bold)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Name` | `Text` | - | - |
| `$Family` | `Text` | - | - |
| `$Size` | `Real` | - | - |
| `$Color` | `Integer` | - | - |
| `$Bold` | `Boolean` | - | - |

**Returns:** `cs.ExcelXMLFileStyle`

---

#### setInteriorColor {#setinteriorcolor}


```4d
Function setInteriorColor($Color : Integer) -> cs.ExcelXMLFileStyle
```

Sets the cell background color with solid pattern

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Color` | `Integer` | - | - |

**Returns:** `cs.ExcelXMLFileStyle`

---

#### setNumberFormat {#setnumberformat}


```4d
Function setNumberFormat($NumberFormat : Text) -> cs.ExcelXMLFileStyle
```

Sets the number format for this style (use NumberFormat_* constants)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$NumberFormat` | `Text` | - | - |

**Returns:** `cs.ExcelXMLFileStyle`

---

#### setAlignment {#setalignment}


```4d
Function setAlignment($Horizontal : Text; $Vertical : Text) -> cs.ExcelXMLFileStyle
```

Sets cell text alignment (defaults to center/center)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Horizontal` | `Text` | - | - |
| `$Vertical` | `Text` | - | - |

**Returns:** `cs.ExcelXMLFileStyle`

---

---

*Generated from ExcelXMLFileStyle.4dm*
