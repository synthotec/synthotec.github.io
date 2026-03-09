---
layout : default
title : MenuItem
parent : Classes
---
# MenuItem [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/MenuItem.4dm)

📊 **Overview:** 12 Properties | 1 Constructor | 2 Functions | 1 Getters

## 📝 Description

Represents a single item in a 4D popup menu, supporting text display with optional bold/italic/underline styling, checkmarks, enable/disable state, formula execution on selection, and variant value return.

🕐 *Last updated: 2026-03-09T14:45:30.110Z*

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
| `_UUID` | `Text` | - | Unique identifier for this menu item |
| `_IsFormulaItem` | `Boolean` | - | True if this item executes a formula when selected |
| `_Formula` | `Variant` | - | Formula or FormulaSet to execute on selection |
| `_IsVariantItem` | `Boolean` | - | True if this item returns a variant value when selected |
| `_Variant` | `Variant` | - | Value to return when item is selected |
| `MenuText` | `Text` | - | Display text for the menu item |
| `Bold` | `Boolean` | - | Apply bold styling to menu text |
| `Italic` | `Boolean` | - | Apply italic styling to menu text |
| `Underline` | `Boolean` | - | Apply underline styling to menu text |
| `Checked` | `Boolean` | - | Display checkmark next to menu item |
| `Enabled` | `Boolean` | - | Enable/disable menu item selection |
| `_IsSeperator` | `Boolean` | - | True if this is a separator line |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($MenuText : Text)
```

Creates a new menu item with the specified display text and default styling

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

Adds this menu item to the specified menu reference with all styling and properties

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MenuReference` | `Text` | - | - |

---

#### _process {#_process}


```4d
Function _process -> Variant
```

Processes menu item selection by returning variant value or executing formula

**Returns:** `Variant`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### _Style {#_style}
 `[🔍 get only]`

```4d
Function get _Style -> Integer
```

Returns combined style flags for 4D menu: 1=Bold, 2=Italic, 4=Underline

**Returns:** `Integer`

---

---

*Generated from MenuItem.4dm*
