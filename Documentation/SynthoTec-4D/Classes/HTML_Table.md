---
layout : default
title : HTML_Table
parent : Classes
---
# HTML_Table [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/HTML_Table.4dm)

📊 **Overview:** 5 Properties | 1 Constructor | 4 Functions

## 📝 Description

Add a new row to the table with optional styling (bold, colors, alignment)

🕐 *Last updated: 2025-12-10T11:45:23.146Z*

---

## 📑 Table of Contents

- [📋 Properties (5)](#properties)
- [🏗️ Constructor](#constructor) (4 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [AddRow](#addrow) (5 params)
    - [Output](#output) → `$Output_table : Text`
    - [HTML_Cell](#html_cell) (7 params) → `Object`
    - [merge](#merge) (2 params)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `RowCollection` | `Collection` | `[]` | Collection of row objects containing cell data |
| `BorderWidth` | `Integer` | `0` | Width of table borders in pixels |
| `CellPadding` | `Integer` | `0` | Cell padding in pixels |
| `UpperCase` | `Boolean` | `False` | Whether to convert cell text to uppercase |
| `Centralize` | `Boolean` | `False` | Whether to center-align table content |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($BorderWidth : Integer; $CellPadding : Integer; $UpperCase : Boolean; $Centralize : Boolean)
```

Initialize HTML table builder with formatting options

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

Add a new row to the table with optional styling (bold, colors, alignment)

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

Generate HTML table markup from RowCollection

**Returns:** `Text`

---

#### HTML_Cell {#html_cell}


```4d
Function HTML_Cell($CellValue : Text; $ForegroundColour : Text; $BackgroundColour : Text; $Alignment : Text; $Strong : Boolean; $RowSpan : Integer; $ColumnSpan : Integer) -> Object
```

Create a cell object with value and optional styling properties

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

Merge vertically adjacent cells with identical values (optional skip first row and ignore columns)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$SkipFirstRow` | `Boolean` | - | - |
| `$ColumnsToIgnore` | `Collection` | - | - |

---

---

*Generated from HTML_Table.4dm*
