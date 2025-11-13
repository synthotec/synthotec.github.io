---
layout : default
title : CollectionObject
parent : Classes
---
# CollectionObject

📊 **Overview:** 1 Constructor | 10 Functions

🕐 *Last updated: 2025-11-13T02:47:32.371Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Functions (10):**

- [CollectionObject](#collectionobject) → `Object`
- [SetIndex](#setindex) (1 param)
- [GetIndex](#getindex) → `Integer`
- [SetPlaceholder](#setplaceholder) (1 param)
- [AppendValue](#appendvalue) (1 param)
- [AppendValueWithPrimaryKey](#appendvaluewithprimarykey) (2 params)
- [AppendValueWithEntity](#appendvaluewithentity) (2 params)
- [GetCurrentValue](#getcurrentvalue) → `Variant`
- [GetCurrentPrimaryKey](#getcurrentprimarykey) → `Integer`
- [GetCurrentEntity](#getcurrententity) → `4D.Entity`

---

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($valuesCollection : Collection; $placeHolderText : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$valuesCollection` | `Collection` | - | - |
| `$placeHolderText` | `Text` | - | - |

---

### ⚙️ Regular Functions

#### CollectionObject {#collectionobject}


```4d
Function CollectionObject -> Object
```

**Returns:** `Object`

---

#### SetIndex {#setindex}


```4d
Function SetIndex($index : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$index` | `Integer` | - | - |

---

#### GetIndex {#getindex}


```4d
Function GetIndex -> Integer
```

**Returns:** `Integer`

---

#### SetPlaceholder {#setplaceholder}


```4d
Function SetPlaceholder($placeHolderText : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$placeHolderText` | `Text` | - | - |

---

#### AppendValue {#appendvalue}


```4d
Function AppendValue($value : Variant)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$value` | `Variant` | - | - |

---

#### AppendValueWithPrimaryKey {#appendvaluewithprimarykey}


```4d
Function AppendValueWithPrimaryKey($value : Variant; $primaryKey : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$value` | `Variant` | - | - |
| `$primaryKey` | `Integer` | - | - |

---

#### AppendValueWithEntity {#appendvaluewithentity}


```4d
Function AppendValueWithEntity($value : Variant; $entity : 4D.Entity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$value` | `Variant` | - | - |
| `$entity` | `4D.Entity` | - | - |

---

#### GetCurrentValue {#getcurrentvalue}


```4d
Function GetCurrentValue -> Variant
```

**Returns:** `Variant`

---

#### GetCurrentPrimaryKey {#getcurrentprimarykey}


```4d
Function GetCurrentPrimaryKey -> Integer
```

**Returns:** `Integer`

---

#### GetCurrentEntity {#getcurrententity}


```4d
Function GetCurrentEntity -> 4D.Entity
```

**Returns:** `4D.Entity`

---

---

*Generated from CollectionObject.4dm*
