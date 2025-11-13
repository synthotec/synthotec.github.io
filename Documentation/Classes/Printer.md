---
layout : default
title : Printer
parent : Classes
---
# Printer

📊 **Overview:** 3 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T12:58:34.306Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (3):**

- [getDefault](#getdefault) (1 param) 🖥️
- [populate](#populate) 🖥️
- [getComputerPrinters](#getcomputerprinters) (1 param) → `cs.PrinterSelection` 🖥️

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

### 📦 Related Classes

- [Printer](Printer.md) - DataClass class
- [PrinterEntity](PrinterEntity.md) - Entity class
- [PrinterSelection](PrinterSelection.md) - EntitySelection class

### 🗂️ Used By Tables

- [Printer](../Tables/Printer.md) - DataClass class

---

*Generated from Printer.4dm*
