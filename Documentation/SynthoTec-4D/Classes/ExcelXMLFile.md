---
layout : default
title : ExcelXMLFile
parent : Classes
---
# ExcelXMLFile [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ExcelXMLFile.4dm)

📊 **Overview:** 7 Properties | 1 Constructor | 7 Functions

## 📝 Description

SetProcessDebugInfo(New collection(ds.getTablePrimaryKeyField($tableNum)->; $BackgroundExpression))

🕐 *Last updated: 2025-11-19T21:53:02.521Z*

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
| `Styles` | `Collection` | `[]` | - |
| `Rows` | `Collection` | `[]` | - |
| `Columns` | `Collection` | `[]` | - |
| `FileContents` | `Text` | `""` | - |
| `FreezeRowsAbove` | `Integer` | `0` | - |
| `FreezeRowsToLeft` | `Integer` | `0` | - |
| `ConditionalFormatting` | `Object` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

## Functions {#functions}

### Regular Functions

#### addSelectionBasedListbox {#addselectionbasedlistbox}


```4d
Function addSelectionBasedListbox($ListboxName : Text)
```

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
