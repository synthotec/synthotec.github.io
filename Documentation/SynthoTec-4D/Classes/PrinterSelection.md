---
layout : default
title : PrinterSelection
parent : Classes
---
# PrinterSelection [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/PrinterSelection.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

Entity selection of printer records, providing a convenience filter to return only those printers with at least one label paper option configured (i.e. label-capable printers).

**Extends:** `EntitySelection`

🕐 *Last updated: 2026-03-09T14:45:30.607Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getLabelPrinters](#getlabelprinters) → `$PrinterSelection : cs.PrinterSelection` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getLabelPrinters {#getlabelprinters}
 `[🖥️ local]`

```4d
Function getLabelPrinters -> $PrinterSelection : cs.PrinterSelection
```

Returns a filtered selection of only label printers

**Returns:** `cs.PrinterSelection`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Printer](../Tables/Printer.md) - ORDA EntitySelection class for Printer table

### � Related Classes

- [Printer](Printer.md) - ORDA DataClass class for Printer table
- [PrinterEntity](PrinterEntity.md) - ORDA Entity class for Printer table

### � Forms

- [PrinterManagement](../Forms/PrinterManagement.md) - Data source for PrinterManagement form

---

*Generated from PrinterSelection.4dm*
