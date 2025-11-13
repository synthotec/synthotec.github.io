---
layout : default
title : Printer
parent : Classes
---
# Printer

📊 **Overview:** 3 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T21:44:53.543Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (3):**

- [getDefault](#getdefault) (1 param) 🖥️
- [populate](#populate) 🖥️
- [getComputerPrinters](#getcomputerprinters) (1 param) → `cs.PrinterSelection` 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (3)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### getDefault {#getdefault}
 `[🖥️ local]`

```4d
Function getDefault($PrinterType : Integer)
```

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

---

#### getComputerPrinters {#getcomputerprinters}
 `[🖥️ local]`

```4d
Function getComputerPrinters($ActivePrintersOnly : Boolean) -> cs.PrinterSelection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ActivePrintersOnly` | `Boolean` | - | - |

**Returns:** `cs.PrinterSelection`

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

*Generated from Printer.4dm*
