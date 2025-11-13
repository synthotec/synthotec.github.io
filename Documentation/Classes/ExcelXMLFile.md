---
layout : default
title : ExcelXMLFile
parent : Classes
---
# ExcelXMLFile

📊 **Overview:** 7 Properties | 1 Constructor | 7 Functions

## 📝 Description

🗨️ SetProcessDebugInfo(New collection(ds.getTablePrimaryKeyField($tableNum)->; $BackgroundExpression))

🕐 *Last updated: 2025-11-13T02:47:32.629Z*

---

## 📑 Table of Contents

### 📋 Properties (7)

- [Styles](#styles) : `Collection`
- [Rows](#rows) : `Collection`
- [Columns](#columns) : `Collection`
- [FileContents](#filecontents) : `Text`
- [FreezeRowsAbove](#freezerowsabove) : `Integer`
- [FreezeRowsToLeft](#freezerowstoleft) : `Integer`
- [ConditionalFormatting](#conditionalformatting) : `Object`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor)

**⚙️ Functions (7):**

- [addSelectionBasedListbox](#addselectionbasedlistbox) (1 param)
- [setFreezePanes](#setfreezepanes) (2 params)
- [addColumn](#addcolumn) (2 params)
- [addRow](#addrow) (1 param)
- [addStyle](#addstyle) (1 param) → `Text`
- [saveToClipboard](#savetoclipboard) (2 params)
- [generate](#generate)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Styles` | `Collection` | `[]` | - |
| `Rows` | `Collection` | `[]` | - |
| `Columns` | `Collection` | `[]` | - |
| `FileContents` | `Text` | `""` | - |
| `FreezeRowsAbove` | `Integer` | `0` | - |
| `FreezeRowsToLeft` | `Integer` | `0` | - |
| `ConditionalFormatting` | `Object` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

### ⚙️ Regular Functions

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
