---
layout : default
title : HTML_Table
parent : Classes
---
# HTML_Table [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/HTML_Table.4dm)

📊 **Overview:** 1 Constructor | 4 Functions

## 📝 Description

var $RowObject : Object
$RowObject:=New object("Collection"; $RowCellCollection; "Bold"; $Bold)

🕐 *Last updated: 2025-11-19T21:53:02.806Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor) (4 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [AddRow](#addrow) (5 params)
    - [Output](#output) → `$Output_table : Text`
    - [HTML_Cell](#html_cell) (7 params) → `Object`
    - [merge](#merge) (2 params)

---

## Constructor {#constructor}

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

## Functions {#functions}

### Regular Functions

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
Function Output -> $Output_table : Text
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

---

*Generated from HTML_Table.4dm*
