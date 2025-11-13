---
layout : default
title : Menu
parent : Classes
---
# Menu

📊 **Overview:** 6 Properties | 1 Constructor | 7 Functions

🕐 *Last updated: 2025-11-13T13:14:51.205Z*

---

## 📑 Table of Contents

### 📋 Properties (6)

- [_MenuItems](#menuitems) : `Collection`
- [_MenuReference](#menureference) : `Text`
- [_SubMenu](#submenu) : `Boolean`
- [_SubMenuText](#submenutext) : `Text`
- [_MenuItemCollection](#menuitemcollection) : `Collection`
- [Cancelled](#cancelled) : `Boolean`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Functions (7):**

- [addSeperator](#addseperator)
- [addVariantItem](#addvariantitem) (2 params) → `cs.MenuItem`
- [addFormulaItem](#addformulaitem) (2 params) → `cs.MenuItem`
- [addSubMenu](#addsubmenu) (1 param) → `cs.Menu`
- [show](#show) → `Variant`
- [_addMenuItems](#_addmenuitems) (1 param)
- [_release](#_release)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `_MenuItems` | `Collection` | - | - |
| `_MenuReference` | `Text` | - | - |
| `_SubMenu` | `Boolean` | - | - |
| `_SubMenuText` | `Text` | - | - |
| `_MenuItemCollection` | `Collection` | - | - |
| `Cancelled` | `Boolean` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

#### addSeperator {#addseperator}


```4d
Function addSeperator
```

---

#### addVariantItem {#addvariantitem}


```4d
Function addVariantItem($MenuText : Text; $Variant : Variant) -> cs.MenuItem
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
Function addFormulaItem($MenuText : Text; $FormulaOrFormulaSet : Variant) -> cs.MenuItem
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
Function addSubMenu($SubMenuText : Text) -> cs.Menu
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$SubMenuText` | `Text` | - | - |

**Returns:** `cs.Menu`

---

#### show {#show}


```4d
Function show -> Variant
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

## 🔗 Related Items

### 📦 Related Classes

- [](.md) - Extends this class

---

*Generated from Menu.4dm*
