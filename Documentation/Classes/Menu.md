---
layout : default
title : Menu
parent : Classes
---
# Menu

📊 **Overview:** 6 Properties | 1 Constructor | 7 Functions

🕐 *Last updated: 2025-11-13T15:02:53.385Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#-properties)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (7):**

- [addSeperator](#addseperator)
- [addVariantItem](#addvariantitem) (2 params) → `$MenuItem : cs.MenuItem`
- [addFormulaItem](#addformulaitem) (2 params) → `$MenuItem : cs.MenuItem`
- [addSubMenu](#addsubmenu) (1 param) → `$Menu : cs.Menu`
- [show](#show) → `$FormulaResult : Variant`
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
