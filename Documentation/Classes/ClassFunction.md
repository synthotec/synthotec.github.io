---
layout : default
title : ClassFunction
parent : Classes
---
# ClassFunction

📊 **Overview:** 1 Constructor | 3 Functions

## 📝 Description

🗨️ Stores metadata about a class function

🕐 *Last updated: 2025-11-13T16:46:51.495Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (3):**

- [addModifier](#addmodifier) (1 param)
- [addParameter](#addparameter) (1 param)
- [toObject](#toobject) → `Object`

---

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Name : Text)
```

Stores metadata about a class function

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Name` | `Text` | - | - |

---

### ⚙️ Regular Functions

#### addModifier {#addmodifier}


```4d
Function addModifier($Modifier : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Modifier` | `Text` | - | - |

---

#### addParameter {#addparameter}


```4d
Function addParameter($Parameter : cs.ClassParameter)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameter` | `cs.ClassParameter` | - | - |

---

#### toObject {#toobject}


```4d
Function toObject -> Object
```

**Returns:** `Object`

---

---

*Generated from ClassFunction.4dm*
