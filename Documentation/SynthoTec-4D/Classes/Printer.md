---
layout : default
title : Printer
parent : Classes
---
# Printer [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Printer.4dm)

📊 **Overview:** 3 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:12.673Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getDefault](#getdefault) (1 param) 🖥️
    - [populate](#populate) 🖥️
    - [getComputerPrinters](#getcomputerprinters) (1 param) → `cs.PrinterSelection` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getDefault {#getdefault}
 `[🖥️ local]`

```4d
Function getDefault($PrinterType : Integer)
```

Gets the default printer for the specified printer type (currently incomplete)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PrinterType` | `Integer` | - | - |

---

#### populate {#populate}
 `[🖥️ local]`

```4d
Function populate
```

Synchronizes printer list from system printers and updates active status in database

---

#### getComputerPrinters {#getcomputerprinters}
 `[🖥️ local]`

```4d
Function getComputerPrinters($ActivePrintersOnly : Boolean) -> cs.PrinterSelection
```

Returns printers for current computer; optionally filters to active printers only

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ActivePrintersOnly` | `Boolean` | - | - |

**Returns:** `cs.PrinterSelection`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Printer](../Tables/Printer.md) - ORDA DataClass class for Printer table

### � Related Classes

- [PrinterEntity](PrinterEntity.md) - ORDA Entity class for Printer table
- [PrinterSelection](PrinterSelection.md) - ORDA EntitySelection class for Printer table

### � Forms

- [PrinterManagement](../Forms/PrinterManagement.md) - Data source for PrinterManagement form

---

*Generated from Printer.4dm*
