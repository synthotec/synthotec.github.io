---
layout : default
title : Menu
parent : Classes
---
# Menu [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Menu.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 7 Functions

## 📝 Description

Creates a new menu with optional collection of text items that return their index when selected

🕐 *Last updated: 2026-01-13T16:04:12.176Z*

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
| `_MenuItems` | `Collection` | - | Collection of MenuItem and submenu objects |
| `_MenuReference` | `Text` | - | 4D menu reference handle |
| `_SubMenu` | `Boolean` | - | True if this menu is a submenu of another |
| `_SubMenuText` | `Text` | - | Display text when this is a submenu |
| `_MenuItemCollection` | `Collection` | - | Flattened collection of all menu items including submenus |
| `Cancelled` | `Boolean` | - | True if user cancelled menu selection |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($BasicMenuItems : Collection)
```

Creates a new menu with optional collection of text items that return their index when selected

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

Adds a separator line to the menu (ignored if menu is empty)

---

#### addVariantItem {#addvariantitem}


```4d
Function addVariantItem($MenuText : Text; $Variant : Variant) -> $MenuItem : cs.MenuItem
```

Adds a menu item that returns a specified variant value when selected

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

Adds a menu item that executes a formula or formula set when selected

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

Adds a submenu with the specified text, returns the new submenu for further item additions

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

Displays the menu and returns the result from the selected item, sets Cancelled if dismissed

**Returns:** `Variant`

---

#### _addMenuItems {#_addmenuitems}


```4d
Function _addMenuItems($ParentMenuReference : Text)
```

Internal method to build 4D menu structure from menu items, handling submenus recursively

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ParentMenuReference` | `Text` | - | - |

---

#### _release {#_release}


```4d
Function _release
```

Releases menu resources, recursively releasing all submenus

---

---

*Generated from Menu.4dm*
