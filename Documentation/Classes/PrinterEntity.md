---
layout : default
title : PrinterEntity
parent : Classes
---
# PrinterEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PrinterEntity.4dm)

📊 **Overview:** 5 Functions | 5 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T00:18:20.955Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [getLabelPaperOptions](#getlabelpaperoptions) → `Collection`
  - [updateOptions](#updateoptions) 🖥️
  - [printJobs](#printjobs) 🖥️
  - [setCurrent](#setcurrent) → `$Success : Boolean` 🖥️
  - [setDefault](#setdefault) 🖥️
  - [LabelPrinter](#labelprinter) → `Boolean`
  - [LabelPaperName](#labelpapername) → `Text`
  - [isLabelPrinter](#islabelprinter) → `Boolean`
  - [isDocumentPrinter](#isdocumentprinter) → `Boolean`
  - [TypeDisplay](#typedisplay) → `Text`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### getLabelPaperOptions {#getlabelpaperoptions}


```4d
Function getLabelPaperOptions -> Collection
```

**Returns:** `Collection`

---

#### updateOptions {#updateoptions}
 `[🖥️ local]`

```4d
Function updateOptions
```

---

#### printJobs {#printjobs}
 `[🖥️ local]`

```4d
Function printJobs
```

---

#### setCurrent {#setcurrent}
 `[🖥️ local]`

```4d
Function setCurrent -> $Success : Boolean
```

**Returns:** `Boolean`

---

#### setDefault {#setdefault}
 `[🖥️ local]`

```4d
Function setDefault
```

---

### Getters

#### LabelPrinter {#labelprinter}
 `[🔍 getter]`

```4d
Function LabelPrinter -> Boolean
```

**Returns:** `Boolean`

---

#### LabelPaperName {#labelpapername}
 `[🔍 getter]`

```4d
Function LabelPaperName -> Text
```

**Returns:** `Text`

---

#### isLabelPrinter {#islabelprinter}
 `[🖥️ local, 🔍 getter]`

```4d
Function isLabelPrinter -> Boolean
```

**Returns:** `Boolean`

---

#### isDocumentPrinter {#isdocumentprinter}
 `[🖥️ local, 🔍 getter]`

```4d
Function isDocumentPrinter -> Boolean
```

**Returns:** `Boolean`

---

#### TypeDisplay {#typedisplay}
 `[🖥️ local, 🔍 getter]`

```4d
Function TypeDisplay -> Text
```

**Returns:** `Text`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Printer](../Tables/Printer.md) - Source table for this ORDA class

### � Related Classes

- [Printer](Printer.md) - ORDA DataClass class for Printer table
- [PrinterSelection](PrinterSelection.md) - ORDA EntitySelection class for Printer table

---

*Generated from PrinterEntity.4dm*
