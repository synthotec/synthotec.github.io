---
layout : default
title : MenuItem
parent : Classes
---
# MenuItem

📊 **Overview:** 12 Properties | 1 Constructor | 2 Functions | 1 Getters

🕐 *Last updated: 2025-11-13T13:33:26.913Z*

---

## 📑 Table of Contents

### 📋 Properties (12)

- [_UUID](#uuid) : `Text`
- [_IsFormulaItem](#isformulaitem) : `Boolean`
- [_Formula](#formula) : `Variant`
- [_IsVariantItem](#isvariantitem) : `Boolean`
- [_Variant](#variant) : `Variant`
- [MenuText](#menutext) : `Text`
- [Bold](#bold) : `Boolean`
- [Italic](#italic) : `Boolean`
- [Underline](#underline) : `Boolean`
- [Checked](#checked) : `Boolean`
- [Enabled](#enabled) : `Boolean`
- [_IsSeperator](#isseperator) : `Boolean`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (2):**

- [_addMenuItem](#_addmenuitem) (1 param)
- [_process](#_process) → `Variant`

**🔍 Getters (1):**

- [_Style](#_style) → `Integer`

### 🔗 Related Items

- [Classes](#-related-classes) (1)

---

## 📋 Properties

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

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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

### 🔍 Getters

#### _Style {#_style}
 `[🔍 getter]`

```4d
Function _Style -> Integer
```

**Returns:** `Integer`

---

## 🔗 Related Items

### 📦 Related Classes

- [](.md) - Extends this class

---

*Generated from MenuItem.4dm*
