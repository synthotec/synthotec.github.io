---
layout : default
title : ClassFunction
parent : Classes
---
# ClassFunction [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ClassFunction.4dm)

📊 **Overview:** 1 Constructor | 3 Functions

## 📝 Description

Stores metadata about a class function

🕐 *Last updated: 2025-11-19T21:53:02.084Z*

---

## 📑 Table of Contents

- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [addModifier](#addmodifier) (1 param)
    - [addParameter](#addparameter) (1 param)
    - [toObject](#toobject) → `Object`

---

## Constructor {#constructor}

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

## Functions {#functions}

### Regular Functions

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
