---
layout : default
title : ExcelXMLFile
parent : Classes
---
# ExcelXMLFile

## Description

🗨️ SetProcessDebugInfo(New collection(ds.getTablePrimaryKeyField($tableNum)->; $BackgroundExpression))

## Table of Contents

### Properties

- [Styles](#styles)
- [Rows](#rows)
- [Columns](#columns)
- [FileContents](#filecontents)
- [FreezeRowsAbove](#freezerowsabove)
- [FreezeRowsToLeft](#freezerowstoleft)
- [ConditionalFormatting](#conditionalformatting)

### Functions

- [constructor() [constructor]](#constructor)
- [addSelectionBasedListbox()](#addselectionbasedlistbox)
- [setFreezePanes()](#setfreezepanes)
- [addColumn()](#addcolumn)
- [addRow()](#addrow)
- [addStyle()](#addstyle)
- [saveToClipboard()](#savetoclipboard)
- [generate()](#generate)

---

## Properties

### Styles {#styles}

**Type:** `Collection`

**Default Value:** `[]`

---

### Rows {#rows}

**Type:** `Collection`

**Default Value:** `[]`

---

### Columns {#columns}

**Type:** `Collection`

**Default Value:** `[]`

---

### FileContents {#filecontents}

**Type:** `Text`

**Default Value:** `""`

---

### FreezeRowsAbove {#freezerowsabove}

**Type:** `Integer`

**Default Value:** `0`

---

### FreezeRowsToLeft {#freezerowstoleft}

**Type:** `Integer`

**Default Value:** `0`

---

### ConditionalFormatting {#conditionalformatting}

**Type:** `Object`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor
```

---

### addSelectionBasedListbox {#addselectionbasedlistbox}


```4d
Function addSelectionBasedListbox($ListboxName : Text)
```

---

### setFreezePanes {#setfreezepanes}


```4d
Function setFreezePanes($RowsAbove : Integer; $RowsToLeft : Integer)
```

---

### addColumn {#addcolumn}


```4d
Function addColumn($Width : Real; $Span : Integer)
```

---

### addRow {#addrow}


```4d
Function addRow($ExcelXMLFileRow : cs.ExcelXMLFileRow)
```

---

### addStyle {#addstyle}


```4d
Function addStyle($NewExcelXMLFileStyle : cs.ExcelXMLFileStyle) -> Text
```

**Returns:** `Text`

---

### saveToClipboard {#savetoclipboard}


```4d
Function saveToClipboard($FileNameWithoutExtension : Text; $ShowAlert : Boolean)
```

---

### generate {#generate}


```4d
Function generate
```

---

---

*Generated from ExcelXMLFile.4dm*
*Last updated: 2025-11-13T00:30:41.449Z*
