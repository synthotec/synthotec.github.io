---
layout : default
title : MenuItem
parent : Classes
---
# MenuItem [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MenuItem.4dm)

📊 **Overview:** 12 Properties | 1 Constructor | 2 Functions | 1 Getters

🕐 *Last updated: 2025-11-19T21:53:03.047Z*

---

## 📑 Table of Contents

- [📋 Properties (12)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [_addMenuItem](#_addmenuitem) (1 param)
    - [_process](#_process) → `Variant`
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [_Style](#_style) 🔍 → `Integer`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `_UUID` | `Text` | - | - |
| `_IsFormulaItem` | `Boolean` | - | - |
| `_Formula` | `Variant` | - | - |
| `_IsVariantItem` | `Boolean` | - | - |
| `_Variant` | `Variant` | - | - |
| `MenuText` | `Text` | - | - |
| `Bold` | `Boolean` | - | - |
| `Italic` | `Boolean` | - | - |
| `Underline` | `Boolean` | - | - |
| `Checked` | `Boolean` | - | - |
| `Enabled` | `Boolean` | - | - |
| `_IsSeperator` | `Boolean` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($MenuText : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MenuText` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### _addMenuItem {#_addmenuitem}


```4d
Function _addMenuItem($MenuReference : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MenuReference` | `Text` | - | - |

---

#### _process {#_process}


```4d
Function _process -> Variant
```

**Returns:** `Variant`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### _Style {#_style}
 `[🔍 get only]`

```4d
Function get _Style -> Integer
```

**Returns:** `Integer`

---

---

*Generated from MenuItem.4dm*
