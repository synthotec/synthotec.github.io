---
layout : default
title : ExcelXMLFileStyle
parent : Classes
---
# ExcelXMLFileStyle

📊 **Overview:** 9 Properties | 1 Constructor | 4 Functions

🕐 *Last updated: 2025-11-13T13:33:26.714Z*

---

## 📑 Table of Contents

### 📋 Properties (9)

- [NumberFormat_ShortDate](#numberformatshortdate) : `Text`
- [NumberFormat_dd_mmm](#numberformatddmmm) : `Text`
- [NumberFormat_Decimal](#numberformatdecimal) : `Text`
- [NumberFormat_Number](#numberformatnumber) : `Text`
- [Font](#font) : `Object`
- [Interior](#interior) : `Object`
- [Alignment](#alignment) : `Object`
- [NumberFormat](#numberformat) : `Text`
- [ID](#id) : `Text`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor)

**⚙️ Regular Functions (4):**

- [setFontStyle](#setfontstyle) (5 params) → `cs.ExcelXMLFileStyle`
- [setInteriorColor](#setinteriorcolor) (1 param) → `cs.ExcelXMLFileStyle`
- [setNumberFormat](#setnumberformat) (1 param) → `cs.ExcelXMLFileStyle`
- [setAlignment](#setalignment) (2 params) → `cs.ExcelXMLFileStyle`

### 🔗 Related Items

- [Classes](#-related-classes) (1)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `NumberFormat_ShortDate` | `Text` | `"Short Date"` | - |
| `NumberFormat_dd_mmm` | `Text` | `"dd\\-mmm"` | - |
| `NumberFormat_Decimal` | `Text` | `"General;#;;@"` | - |
| `NumberFormat_Number` | `Text` | `"#,###,###,##0"` | - |
| `Font` | `Object` | `{}` | - |
| `Interior` | `Object` | `{}` | - |
| `Alignment` | `Object` | `{}` | - |
| `NumberFormat` | `Text` | `"General"` | - |
| `ID` | `Text` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

### ⚙️ Regular Functions

#### setFontStyle {#setfontstyle}


```4d
Function setFontStyle($Name : Text; $Family : Text; $Size : Real; $Color : Integer; $Bold : Boolean) -> cs.ExcelXMLFileStyle
```

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

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Horizontal` | `Text` | - | - |
| `$Vertical` | `Text` | - | - |

**Returns:** `cs.ExcelXMLFileStyle`

---

## 🔗 Related Items

### 📦 Related Classes

- [](.md) - Extends this class

---

*Generated from ExcelXMLFileStyle.4dm*
