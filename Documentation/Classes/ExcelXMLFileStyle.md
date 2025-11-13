---
layout : default
title : ExcelXMLFileStyle
parent : Classes
---
# ExcelXMLFileStyle

## Table of Contents

### Properties

- [NumberFormat_ShortDate](#numberformatshortdate)
- [NumberFormat_dd_mmm](#numberformatddmmm)
- [NumberFormat_Decimal](#numberformatdecimal)
- [NumberFormat_Number](#numberformatnumber)
- [Font](#font)
- [Interior](#interior)
- [Alignment](#alignment)
- [NumberFormat](#numberformat)
- [ID](#id)

### Functions

- [constructor() [constructor]](#constructor)
- [setFontStyle()](#setfontstyle)
- [setInteriorColor()](#setinteriorcolor)
- [setNumberFormat()](#setnumberformat)
- [setAlignment()](#setalignment)

---

## Properties

### NumberFormat_ShortDate {#numberformatshortdate}

**Type:** `Text`

**Default Value:** `"Short Date"`

---

### NumberFormat_dd_mmm {#numberformatddmmm}

**Type:** `Text`

**Default Value:** `"dd\\-mmm"`

---

### NumberFormat_Decimal {#numberformatdecimal}

**Type:** `Text`

**Default Value:** `"General;#;;@"`

---

### NumberFormat_Number {#numberformatnumber}

**Type:** `Text`

**Default Value:** `"#,###,###,##0"`

---

### Font {#font}

**Type:** `Object`

**Default Value:** `{}`

---

### Interior {#interior}

**Type:** `Object`

**Default Value:** `{}`

---

### Alignment {#alignment}

**Type:** `Object`

**Default Value:** `{}`

---

### NumberFormat {#numberformat}

**Type:** `Text`

**Default Value:** `"General"`

---

### ID {#id}

**Type:** `Text`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor
```

---

### setFontStyle {#setfontstyle}


```4d
Function setFontStyle($Name : Text; $Family : Text; $Size : Real; $Color : Integer; $Bold : Boolean) -> cs.ExcelXMLFileStyle
```

**Returns:** `cs.ExcelXMLFileStyle`

---

### setInteriorColor {#setinteriorcolor}


```4d
Function setInteriorColor($Color : Integer) -> cs.ExcelXMLFileStyle
```

**Returns:** `cs.ExcelXMLFileStyle`

---

### setNumberFormat {#setnumberformat}


```4d
Function setNumberFormat($NumberFormat : Text) -> cs.ExcelXMLFileStyle
```

**Returns:** `cs.ExcelXMLFileStyle`

---

### setAlignment {#setalignment}


```4d
Function setAlignment($Horizontal : Text; $Vertical : Text) -> cs.ExcelXMLFileStyle
```

**Returns:** `cs.ExcelXMLFileStyle`

---

---

*Generated from ExcelXMLFileStyle.4dm*
*Last updated: 2025-11-13T00:30:41.474Z*
