---
layout : default
title : FormulaSet
parent : Classes
---
# FormulaSet [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/FormulaSet.4dm)

📊 **Overview:** 4 Properties | 1 Constructor | 1 Functions

## 📝 Description

Creates formula set from single formula or collection of formulas with optional this object and parameters

🕐 *Last updated: 2026-01-13T16:04:11.939Z*

---

## 📑 Table of Contents

- [📋 Properties (4)](#properties)
- [🏗️ Constructor](#constructor) (3 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [apply](#apply) → `$LastFormulaResult : Variant`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `_FormulaCollection` | `Collection` | - | Internal collection of formulas to execute |
| `_ThisObject` | `4D.Function` | - | TBI: appears to be Object not Function based on constructor |
| `_Parameters` | `Collection` | - | Parameters to pass to each formula |
| `FormulaResults` | `Collection` | - | Results from executing all formulas in the set |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($FormulaOrFormulaCollection : Variant; $ThisObject : Object; $Parameters : Collection)
```

Creates formula set from single formula or collection of formulas with optional this object and parameters

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FormulaOrFormulaCollection` | `Variant` | - | - |
| `$ThisObject` | `Object` | - | - |
| `$Parameters` | `Collection` | - | - |

---

## Functions {#functions}

### Regular Functions

#### apply {#apply}


```4d
Function apply -> $LastFormulaResult : Variant
```

Applies all formulas in the set and returns the result of the last formula

**Returns:** `Variant`

---

---

*Generated from FormulaSet.4dm*
