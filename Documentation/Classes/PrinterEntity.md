---
layout : default
title : PrinterEntity
parent : Classes
---
# PrinterEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PrinterEntity.4dm)

📊 **Overview:** 5 Functions | 5 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:35:59.052Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [getLabelPaperOptions](#getlabelpaperoptions) → `Collection`
  - [updateOptions](#updateoptions) 🖥️
  - [printJobs](#printjobs) 🖥️
  - [setCurrent](#setcurrent) → `$Success : Boolean` 🖥️
  - [setDefault](#setdefault) 🖥️
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

### Properties (Getters/Setters/Query/OrderBy)

#### isDocumentPrinter {#isdocumentprinter}
 `[🔍 get only, 🖥️ local]`

```4d
Function get isDocumentPrinter -> Boolean
```

**Returns:** `Boolean`

---

#### isLabelPrinter {#islabelprinter}
 `[🔍 get only, 🖥️ local]`

```4d
Function get isLabelPrinter -> Boolean
```

**Returns:** `Boolean`

---

#### LabelPaperName {#labelpapername}
 `[🔍 get only]`

```4d
Function get LabelPaperName -> Text
```

**Returns:** `Text`

---

#### LabelPrinter {#labelprinter}
 `[🔍 get only]`

```4d
Function get LabelPrinter -> Boolean
```

**Returns:** `Boolean`

---

#### TypeDisplay {#typedisplay}
 `[🔍 get only, 🖥️ local]`

```4d
Function get TypeDisplay -> Text
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
