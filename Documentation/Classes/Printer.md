---
layout : default
title : Printer
parent : Classes
---
# Printer

📊 **Overview:** 3 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T01:17:24.101Z*

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

---

*Generated from Printer.4dm*
