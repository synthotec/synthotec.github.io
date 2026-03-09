---
layout : default
title : EntitySelectionMenu
parent : Classes
---
# EntitySelectionMenu [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/EntitySelectionMenu.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions | 1 Getters | 1 Setters

## 📝 Description

Creates and displays a dynamic 4D popup menu populated from an entity selection, ordered by a specified display property. Returns the selected entity, or Null if the user cancels or no selection is made.

🕐 *Last updated: 2026-03-09T14:45:29.559Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [display](#display) (1 param) → `4D.Entity`
    - [displayWithParents](#displaywithparents) (2 params) → `4D.Entity`
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [selectedEntity](#selectedentity) 🔍 ✏️ → `4D.Entity`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `EntitySelection` | `4D.EntitySelection` | - | Entity selection to display in menu |
| `_selectedEntity` | `4D.Entity` | - | Currently selected entity from the menu |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($EntitySelection : 4D.EntitySelection; $ParentPath : Text)
```

Creates a dynamic popup menu for selecting entities from an entity selection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntitySelection` | `4D.EntitySelection` | - | - |
| `$ParentPath` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### display {#display}


```4d
Function display($DisplayTextProperty : Object) -> 4D.Entity
```

Displays a popup menu with entities sorted by display property, returns selected entity or Null

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DisplayTextProperty` | `Object` | - | - |

**Returns:** `4D.Entity`

---

#### displayWithParents {#displaywithparents}


```4d
Function displayWithParents($DisplayTextProperty : Object; $ParentProperty : Object) -> 4D.Entity
```

Displays hierarchical popup menu grouped by parent property, returns selected entity or Null

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DisplayTextProperty` | `Object` | - | - |
| `$ParentProperty` | `Object` | - | - |

**Returns:** `4D.Entity`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### selectedEntity {#selectedentity}
 `[🔍 get, ✏️ set]`

```4d
Function get selectedEntity -> 4D.Entity
Function set selectedEntity($SelectedEntity : 4D.Entity)
```

Returns the currently selected entity

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$SelectedEntity` | `4D.Entity` | - |

**Returns:** `4D.Entity`

---

---

*Generated from EntitySelectionMenu.4dm*
