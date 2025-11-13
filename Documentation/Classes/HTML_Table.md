---
layout : default
title : HTML_Table
parent : Classes
---
# HTML_Table

📊 **Overview:** 1 Constructor | 4 Functions

## 📝 Description

🗨️ var $RowObject : Object
$RowObject:=New object("Collection"; $RowCellCollection; "Bold"; $Bold)

🕐 *Last updated: 2025-11-13T13:33:26.822Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (4 params)

**⚙️ Regular Functions (4):**

- [AddRow](#addrow) (5 params)
- [Output](#output) → `Text`
- [HTML_Cell](#html_cell) (7 params) → `Object`
- [merge](#merge) (2 params)

### 🔗 Related Items

- [Classes](#-related-classes) (1)

---

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($BorderWidth : Integer; $CellPadding : Integer; $UpperCase : Boolean; $Centralize : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BorderWidth` | `Integer` | - | - |
| `$CellPadding` | `Integer` | - | - |
| `$UpperCase` | `Boolean` | - | - |
| `$Centralize` | `Boolean` | - | - |

---

### ⚙️ Regular Functions

#### AddRow {#addrow}


```4d
Function AddRow($RowCellCollection : Collection; $Bold : Boolean; $ForegroundColour : Text; $BackgroundColour : Text; $Alignment : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RowCellCollection` | `Collection` | - | - |
| `$Bold` | `Boolean` | - | - |
| `$ForegroundColour` | `Text` | - | - |
| `$BackgroundColour` | `Text` | - | - |
| `$Alignment` | `Text` | - | - |

---

#### Output {#output}


```4d
Function Output -> Text
```

**Returns:** `Text`

---

#### HTML_Cell {#html_cell}


```4d
Function HTML_Cell($CellValue : Text; $ForegroundColour : Text; $BackgroundColour : Text; $Alignment : Text; $Strong : Boolean; $RowSpan : Integer; $ColumnSpan : Integer) -> Object
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CellValue` | `Text` | - | - |
| `$ForegroundColour` | `Text` | - | - |
| `$BackgroundColour` | `Text` | - | - |
| `$Alignment` | `Text` | - | - |
| `$Strong` | `Boolean` | - | - |
| `$RowSpan` | `Integer` | - | - |
| `$ColumnSpan` | `Integer` | - | - |

**Returns:** `Object`

---

#### merge {#merge}


```4d
Function merge($SkipFirstRow : Boolean; $ColumnsToIgnore : Collection)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$SkipFirstRow` | `Boolean` | - | - |
| `$ColumnsToIgnore` | `Collection` | - | - |

---

## 🔗 Related Items

### 📦 Related Classes

- [](.md) - Extends this class

---

*Generated from HTML_Table.4dm*
