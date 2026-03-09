---
layout : default
title : PrinterEntity
parent : Classes
---
# PrinterEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PrinterEntity.4dm)

📊 **Overview:** 5 Functions | 5 Getters

## 📝 Description

Entity representing a system printer, with helpers to determine if it supports label printing (based on configured paper options) and to retrieve available label paper sizes for the Zebra/label workflow.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.595Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getLabelPaperOptions](#getlabelpaperoptions) → `Collection`
    - [updateOptions](#updateoptions) 🖥️
    - [printJobs](#printjobs) 🖥️
    - [setCurrent](#setcurrent) → `$Success : Boolean` 🖥️
    - [setDefault](#setdefault) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [isDocumentPrinter](#isdocumentprinter) 🔍 → `Boolean`
    - [isLabelPrinter](#islabelprinter) 🔍 → `Boolean`
    - [LabelPaperName](#labelpapername) 🔍 → `Text`
    - [LabelPrinter](#labelprinter) 🔍 → `Boolean`
    - [TypeDisplay](#typedisplay) 🔍 → `Text`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getLabelPaperOptions {#getlabelpaperoptions}


```4d
Function getLabelPaperOptions -> Collection
```

Returns a collection of label paper options with 709x291 dimensions from printer options

**Returns:** `Collection`

---

#### updateOptions {#updateoptions}
 `[🖥️ local]`

```4d
Function updateOptions
```

Reads printer paper and source options from system and updates the printer's configuration

---

#### printJobs {#printjobs}
 `[🖥️ local]`

```4d
Function printJobs
```

Prints all pending print jobs for this printer, grouped by paper type

---

#### setCurrent {#setcurrent}
 `[🖥️ local]`

```4d
Function setCurrent -> $Success : Boolean
```

Sets this printer as the current printer for printing operations

**Returns:** `Boolean`

---

#### setDefault {#setdefault}
 `[🖥️ local]`

```4d
Function setDefault
```

Sets this printer as the default printer (currently incomplete)

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### isDocumentPrinter {#isdocumentprinter}
 `[🔍 get only, 🖥️ local]`

```4d
Function get isDocumentPrinter -> Boolean
```

Returns true if printer type is set to Document

**Returns:** `Boolean`

---

#### isLabelPrinter {#islabelprinter}
 `[🔍 get only, 🖥️ local]`

```4d
Function get isLabelPrinter -> Boolean
```

Returns true if printer type is set to Label

**Returns:** `Boolean`

---

#### LabelPaperName {#labelpapername}
 `[🔍 get only]`

```4d
Function get LabelPaperName -> Text
```

Returns the name of the first available label paper option, or empty string if none

**Returns:** `Text`

---

#### LabelPrinter {#labelprinter}
 `[🔍 get only]`

```4d
Function get LabelPrinter -> Boolean
```

Returns true if this printer has label paper options configured

**Returns:** `Boolean`

---

#### TypeDisplay {#typedisplay}
 `[🔍 get only, 🖥️ local]`

```4d
Function get TypeDisplay -> Text
```

Returns a human-readable display string for the printer type

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Printer](../Tables/Printer.md) - ORDA Entity class for Printer table

### � Related Classes

- [Printer](Printer.md) - ORDA DataClass class for Printer table
- [PrinterSelection](PrinterSelection.md) - ORDA EntitySelection class for Printer table

### � Forms

- [PrinterManagement](../Forms/PrinterManagement.md) - Data source for PrinterManagement form

---

*Generated from PrinterEntity.4dm*
