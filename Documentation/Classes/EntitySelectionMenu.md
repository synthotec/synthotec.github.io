---
layout : default
title : EntitySelectionMenu
parent : Classes
---
# EntitySelectionMenu

## Table of Contents

### Properties

- [EntitySelection](#entityselection)
- [_selectedEntity](#selectedentity)

### Functions

- [constructor() [constructor]](#constructor)
- [display()](#display)
- [displayWithParents()](#displaywithparents)
- [selectedEntity() [setter]](#selectedentity)
- [selectedEntity() [getter]](#selectedentity)

---

## Properties

### EntitySelection {#entityselection}

**Type:** `4D.EntitySelection`

---

### _selectedEntity {#selectedentity}

**Type:** `4D.Entity`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($EntitySelection : 4D.EntitySelection; $ParentPath : Text)
```

---

### display {#display}


```4d
Function display($DisplayTextProperty : Object) -> 4D.Entity
```

**Returns:** `4D.Entity`

---

### displayWithParents {#displaywithparents}


```4d
Function displayWithParents($DisplayTextProperty : Object; $ParentProperty : Object) -> 4D.Entity
```

**Returns:** `4D.Entity`

---

### selectedEntity {#selectedentity}
 `[setter]`

```4d
Function selectedEntity($SelectedEntity : 4D.Entity)
```

---

### selectedEntity {#selectedentity}
 `[getter]`

```4d
Function selectedEntity -> 4D.Entity
```

**Returns:** `4D.Entity`

---

---

*Generated from EntitySelectionMenu.4dm*
*Last updated: 2025-11-13T00:30:41.330Z*
