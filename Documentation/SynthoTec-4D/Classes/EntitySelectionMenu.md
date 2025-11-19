---
layout : default
title : EntitySelectionMenu
parent : Classes
---
# EntitySelectionMenu [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/EntitySelectionMenu.4dm)

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions | 1 Getters | 1 Setters

🕐 *Last updated: 2025-11-19T18:12:02.725Z*

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
| `EntitySelection` | `4D.EntitySelection` | - | - |
| `_selectedEntity` | `4D.Entity` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($EntitySelection : 4D.EntitySelection; $ParentPath : Text)
```

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

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$SelectedEntity` | `4D.Entity` | - |

**Returns:** `4D.Entity`

---

---

*Generated from EntitySelectionMenu.4dm*
