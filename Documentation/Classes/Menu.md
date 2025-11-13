---
layout : default
title : Menu
parent : Classes
---
# Menu

## Table of Contents

### Properties

- [_MenuItems](#menuitems)
- [_MenuReference](#menureference)
- [_SubMenu](#submenu)
- [_SubMenuText](#submenutext)
- [_MenuItemCollection](#menuitemcollection)
- [Cancelled](#cancelled)

### Functions

- [constructor() [constructor]](#constructor)
- [addSeperator()](#addseperator)
- [addVariantItem()](#addvariantitem)
- [addFormulaItem()](#addformulaitem)
- [addSubMenu()](#addsubmenu)
- [show()](#show)
- [_addMenuItems()](#_addmenuitems)
- [_release()](#_release)

---

## Properties

### _MenuItems {#menuitems}

**Type:** `Collection`

---

### _MenuReference {#menureference}

**Type:** `Text`

---

### _SubMenu {#submenu}

**Type:** `Boolean`

---

### _SubMenuText {#submenutext}

**Type:** `Text`

---

### _MenuItemCollection {#menuitemcollection}

**Type:** `Collection`

---

### Cancelled {#cancelled}

**Type:** `Boolean`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($BasicMenuItems : Collection)
```

---

### addSeperator {#addseperator}


```4d
Function addSeperator
```

---

### addVariantItem {#addvariantitem}


```4d
Function addVariantItem($MenuText : Text; $Variant : Variant) -> cs.MenuItem
```

**Returns:** `cs.MenuItem`

---

### addFormulaItem {#addformulaitem}


```4d
Function addFormulaItem($MenuText : Text; $FormulaOrFormulaSet : Variant) -> cs.MenuItem
```

**Returns:** `cs.MenuItem`

---

### addSubMenu {#addsubmenu}


```4d
Function addSubMenu($SubMenuText : Text) -> cs.Menu
```

**Returns:** `cs.Menu`

---

### show {#show}


```4d
Function show -> Variant
```

**Returns:** `Variant`

---

### _addMenuItems {#_addmenuitems}


```4d
Function _addMenuItems($ParentMenuReference : Text)
```

---

### _release {#_release}


```4d
Function _release
```

---

---

*Generated from Menu.4dm*
*Last updated: 2025-11-13T00:30:41.827Z*
