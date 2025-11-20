---
layout : default
title : ExcelXMLFileRow
parent : Classes
---
# ExcelXMLFileRow [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ExcelXMLFileRow.4dm)

📊 **Overview:** 4 Properties | 1 Constructor | 1 Functions

## 📝 Description

Adds a cell to this row with value, type, style ID, and optional formula

🕐 *Last updated: 2025-11-20T14:23:48.956Z*

---

## 📑 Table of Contents

- [📋 Properties (4)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [addCell](#addcell) (4 params)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Cells` | `Collection` | `[]` | Collection of cell objects for this row |
| `CellType_Number` | `Text` | `"Number"` | Constant for numeric cell type |
| `CellType_String` | `Text` | `"String"` | Constant for string cell type |
| `CellType_ISODateTime` | `Text` | `"DateTime"` | Constant for ISO date/time cell type |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Creates a new Excel row with empty cells collection and cell type constants

---

## Functions {#functions}

### Regular Functions

#### addCell {#addcell}


```4d
Function addCell($Value : Text; $Type : Text; $StyleID : Text; $Formula : Text)
```

Adds a cell to this row with value, type, style ID, and optional formula

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Value` | `Text` | - | - |
| `$Type` | `Text` | - | - |
| `$StyleID` | `Text` | - | - |
| `$Formula` | `Text` | - | - |

---

---

*Generated from ExcelXMLFileRow.4dm*
