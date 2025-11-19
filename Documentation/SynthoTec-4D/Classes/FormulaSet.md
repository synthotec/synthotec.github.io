---
layout : default
title : FormulaSet
parent : Classes
---
# FormulaSet [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/FormulaSet.4dm)

📊 **Overview:** 4 Properties | 1 Constructor | 1 Functions

🕐 *Last updated: 2025-11-19T18:12:02.914Z*

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
| `_FormulaCollection` | `Collection` | - | - |
| `_ThisObject` | `4D.Function` | - | - |
| `_Parameters` | `Collection` | - | - |
| `FormulaResults` | `Collection` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($FormulaOrFormulaCollection : Variant; $ThisObject : Object; $Parameters : Collection)
```

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

**Returns:** `Variant`

---

---

*Generated from FormulaSet.4dm*
