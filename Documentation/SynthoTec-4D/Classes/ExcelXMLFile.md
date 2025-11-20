---
layout : default
title : ExcelXMLFile
parent : Classes
---
# ExcelXMLFile [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ExcelXMLFile.4dm)

📊 **Overview:** 7 Properties | 1 Constructor | 7 Functions

## 📝 Description

Converts a 4D selection-based listbox to Excel rows with styled cells matching listbox appearance

🕐 *Last updated: 2025-11-20T14:23:48.951Z*

---

## 📑 Table of Contents

- [📋 Properties (7)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [addSelectionBasedListbox](#addselectionbasedlistbox) (1 param)
    - [setFreezePanes](#setfreezepanes) (2 params)
    - [addColumn](#addcolumn) (2 params)
    - [addRow](#addrow) (1 param)
    - [addStyle](#addstyle) (1 param) → `Text`
    - [saveToClipboard](#savetoclipboard) (2 params)
    - [generate](#generate)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Styles` | `Collection` | `[]` | Collection of ExcelXMLFileStyle objects for cell formatting |
| `Rows` | `Collection` | `[]` | Collection of ExcelXMLFileRow objects representing worksheet rows |
| `Columns` | `Collection` | `[]` | Collection of column width definitions |
| `FileContents` | `Text` | `""` | Generated XML content for Excel file |
| `FreezeRowsAbove` | `Integer` | `0` | Number of rows to freeze at top of worksheet |
| `FreezeRowsToLeft` | `Integer` | `0` | Number of columns to freeze at left of worksheet |
| `ConditionalFormatting` | `Object` | - | Conditional formatting rules for cells |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Creates a new Excel XML file object with empty collections

---

## Functions {#functions}

### Regular Functions

#### addSelectionBasedListbox {#addselectionbasedlistbox}


```4d
Function addSelectionBasedListbox($ListboxName : Text)
```

Converts a 4D selection-based listbox to Excel rows with styled cells matching listbox appearance

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ListboxName` | `Text` | - | - |

---

#### setFreezePanes {#setfreezepanes}


```4d
Function setFreezePanes($RowsAbove : Integer; $RowsToLeft : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RowsAbove` | `Integer` | - | - |
| `$RowsToLeft` | `Integer` | - | - |

---

#### addColumn {#addcolumn}


```4d
Function addColumn($Width : Real; $Span : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Width` | `Real` | - | - |
| `$Span` | `Integer` | - | - |

---

#### addRow {#addrow}


```4d
Function addRow($ExcelXMLFileRow : cs.ExcelXMLFileRow)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ExcelXMLFileRow` | `cs.ExcelXMLFileRow` | - | - |

---

#### addStyle {#addstyle}


```4d
Function addStyle($NewExcelXMLFileStyle : cs.ExcelXMLFileStyle) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$NewExcelXMLFileStyle` | `cs.ExcelXMLFileStyle` | - | - |

**Returns:** `Text`

---

#### saveToClipboard {#savetoclipboard}


```4d
Function saveToClipboard($FileNameWithoutExtension : Text; $ShowAlert : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FileNameWithoutExtension` | `Text` | - | - |
| `$ShowAlert` | `Boolean` | - | - |

---

#### generate {#generate}


```4d
Function generate
```

---

---

*Generated from ExcelXMLFile.4dm*
