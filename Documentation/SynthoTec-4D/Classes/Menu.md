---
layout : default
title : Menu
parent : Classes
---
# Menu [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Menu.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 7 Functions

🕐 *Last updated: 2025-11-19T18:10:06.439Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [addSeperator](#addseperator)
    - [addVariantItem](#addvariantitem) (2 params) → `$MenuItem : cs.MenuItem`
    - [addFormulaItem](#addformulaitem) (2 params) → `$MenuItem : cs.MenuItem`
    - [addSubMenu](#addsubmenu) (1 param) → `$Menu : cs.Menu`
    - [show](#show) → `$FormulaResult : Variant`
    - [_addMenuItems](#_addmenuitems) (1 param)
    - [_release](#_release)
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `_MenuItems` | `Collection` | - | - |
| `_MenuReference` | `Text` | - | - |
| `_SubMenu` | `Boolean` | - | - |
| `_SubMenuText` | `Text` | - | - |
| `_MenuItemCollection` | `Collection` | - | - |
| `Cancelled` | `Boolean` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($BasicMenuItems : Collection)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BasicMenuItems` | `Collection` | - | - |

---

## Functions {#functions}

### Regular Functions

#### addSeperator {#addseperator}


```4d
Function addSeperator
```

---

#### addVariantItem {#addvariantitem}


```4d
Function addVariantItem($MenuText : Text; $Variant : Variant) -> $MenuItem : cs.MenuItem
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MenuText` | `Text` | - | - |
| `$Variant` | `Variant` | - | - |

**Returns:** `cs.MenuItem`

---

#### addFormulaItem {#addformulaitem}


```4d
Function addFormulaItem($MenuText : Text; $FormulaOrFormulaSet : Variant) -> $MenuItem : cs.MenuItem
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MenuText` | `Text` | - | - |
| `$FormulaOrFormulaSet` | `Variant` | - | - |

**Returns:** `cs.MenuItem`

---

#### addSubMenu {#addsubmenu}


```4d
Function addSubMenu($SubMenuText : Text) -> $Menu : cs.Menu
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$SubMenuText` | `Text` | - | - |

**Returns:** `cs.Menu`

---

#### show {#show}


```4d
Function show -> $FormulaResult : Variant
```

**Returns:** `Variant`

---

#### _addMenuItems {#_addmenuitems}


```4d
Function _addMenuItems($ParentMenuReference : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ParentMenuReference` | `Text` | - | - |

---

#### _release {#_release}


```4d
Function _release
```

---

---

*Generated from Menu.4dm*
