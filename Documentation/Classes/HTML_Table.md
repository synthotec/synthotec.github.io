# HTML_Table

## Description

var $RowObject : Object
$RowObject:=New object("Collection"; $RowCellCollection; "Bold"; $Bold)

## Table of Contents

### Functions

- [AddRow()](#addrow)
- [Output()](#output)
- [HTML_Cell()](#html_cell)
- [merge()](#merge)

---

## Functions

### AddRow {#addrow}


```4d
Function AddRow($RowCellCollection : Collection; $Bold : Boolean; $ForegroundColour : Text; $BackgroundColour : Text; $Alignment : Text)
```

---

### Output {#output}


```4d
Function Output -> Text
```

**Returns:** `Text`

---

### HTML_Cell {#html_cell}


```4d
Function HTML_Cell($CellValue : Text; $ForegroundColour : Text; $BackgroundColour : Text; $Alignment : Text; $Strong : Boolean; $RowSpan : Integer; $ColumnSpan : Integer) -> Object
```

**Returns:** `Object`

---

### merge {#merge}


```4d
Function merge($SkipFirstRow : Boolean; $ColumnsToIgnore : Collection)
```

---

---

*Generated from HTML_Table.4dm*
*Last updated: 2025-11-12T17:04:21.810Z*
