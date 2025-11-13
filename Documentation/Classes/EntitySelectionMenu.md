---
layout : default
title : EntitySelectionMenu
parent : Classes
---
# EntitySelectionMenu

📊 **Overview:** 2 Properties | 1 Constructor | 2 Functions | 1 Getters | 1 Setters

🕐 *Last updated: 2025-11-13T16:07:42.374Z*

---

## 📑 Table of Contents

- [📋 Properties (2)](#-properties)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Regular Functions (2):**

- [display](#display) (1 param) → `4D.Entity`
- [displayWithParents](#displaywithparents) (2 params) → `4D.Entity`

**🔍 Getters (1):**

- [selectedEntity](#selectedentity) → `4D.Entity`

**✏️ Setters (1):**

- [selectedEntity](#selectedentity) (1 param)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `EntitySelection` | `4D.EntitySelection` | - | - |
| `_selectedEntity` | `4D.Entity` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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

### 🔍 Getters

#### selectedEntity {#selectedentity}
 `[🔍 getter]`

```4d
Function selectedEntity -> 4D.Entity
```

**Returns:** `4D.Entity`

---

### ✏️ Setters

#### selectedEntity {#selectedentity}
 `[✏️ setter]`

```4d
Function selectedEntity($SelectedEntity : 4D.Entity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$SelectedEntity` | `4D.Entity` | - | - |

---

---

*Generated from EntitySelectionMenu.4dm*
