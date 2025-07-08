---
layout: default
title: HTML_Table
parent: Classes
---

# HTML_Table

|   |
|:---|
|[**.new**( *BorderWidth* : Integer; *CellPadding* : Integer; *UpperCase* : Boolean; *Centralize* : Boolean )](#new)<br>|
|[**.Output**()->Output_table : Text](#output)<br>|
|[**.AddRow**( *RowCellCollection* : Collection; *Bold* : Boolean; *ForegroundColour* : Text; *BackgroundColour* : Text; *Alignment* : Text )](#addrow)<br>|
|[**.merge**( *SkipFirstRow* : Boolean; *ColumnsToIgnore* : Collection )](#merge)<br>|
|[**.HTML_Cell**( *CellValue* : Text; *ForegroundColour* : Text; *BackgroundColour* : Text; *Alignment* : Text; *Strong* : Boolean; *RowSpan* : Integer; *ColumnSpan* : Integer ) : Object](#html_cell)<br>|


## new()
**.new**( *BorderWidth* : Integer; *CellPadding* : Integer; *UpperCase* : Boolean; *Centralize* : Boolean )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|BorderWidth|Integer|->|<Description>|
|CellPadding|Integer|->|<Description>|
|UpperCase|Boolean|->|<Description>|
|Centralize|Boolean|->|<Description>|

## Output()
**.Output**()->Output_table : Text

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Output_table|Text|<-|<Description>|

## AddRow()
**.AddRow**( *RowCellCollection* : Collection; *Bold* : Boolean; *ForegroundColour* : Text; *BackgroundColour* : Text; *Alignment* : Text )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|RowCellCollection|Collection|->|<Description>|
|Bold|Boolean|->|<Description>|
|ForegroundColour|Text|->|<Description>|
|BackgroundColour|Text|->|<Description>|
|Alignment|Text|->|<Description>|

## merge()
**.merge**( *SkipFirstRow* : Boolean; *ColumnsToIgnore* : Collection )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|SkipFirstRow|Boolean|->|<Description>|
|ColumnsToIgnore|Collection|->|<Description>|

## HTML_Cell()
**.HTML_Cell**( *CellValue* : Text; *ForegroundColour* : Text; *BackgroundColour* : Text; *Alignment* : Text; *Strong* : Boolean; *RowSpan* : Integer; *ColumnSpan* : Integer ) : Object

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|CellValue|Text|->|<Description>|
|ForegroundColour|Text|->|<Description>|
|BackgroundColour|Text|->|<Description>|
|Alignment|Text|->|<Description>|
|Strong|Boolean|->|<Description>|
|RowSpan|Integer|->|<Description>|
|ColumnSpan|Integer|->|<Description>|
||Object|<-|<Description>|
