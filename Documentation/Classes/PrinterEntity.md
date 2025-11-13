---
layout : default
title : PrinterEntity
parent : Classes
---
# PrinterEntity

📊 **Overview:** 5 Functions | 5 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T21:44:53.589Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (5):**

- [getLabelPaperOptions](#getlabelpaperoptions) → `Collection`
- [updateOptions](#updateoptions) 🖥️
- [printJobs](#printjobs) 🖥️
- [setCurrent](#setcurrent) → `$Success : Boolean` 🖥️
- [setDefault](#setdefault) 🖥️

**🔍 Getters (5):**

- [LabelPrinter](#labelprinter) → `Boolean`
- [LabelPaperName](#labelpapername) → `Text`
- [isLabelPrinter](#islabelprinter) → `Boolean`
- [isDocumentPrinter](#isdocumentprinter) → `Boolean`
- [TypeDisplay](#typedisplay) → `Text`

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (3)

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

### 🔍 Getters

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

## 🔗 Related Items

### 🗂️ Tables

- [Printer](../Tables/Printer.md) - Source table for this ORDA class
- [Printer](../Tables/Printer.md) - Database table storing Printer records

### � Related Classes

- [Printer](Printer.md) - ORDA DataClass class for Printer table
- [PrinterEntity](PrinterEntity.md) - ORDA Entity class for Printer table
- [PrinterSelection](PrinterSelection.md) - ORDA EntitySelection class for Printer table

---

*Generated from PrinterEntity.4dm*
