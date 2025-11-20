---
layout : default
title : CollectionObject
parent : Classes
---
# CollectionObject [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CollectionObject.4dm)

📊 **Overview:** 3 Properties | 1 Constructor | 10 Functions

## 📝 Description

Creates a collection wrapper for UI dropdowns with optional placeholder text

🕐 *Last updated: 2025-11-20T14:23:48.719Z*

---

## 📑 Table of Contents

- [📋 Properties (3)](#properties)
- [🏗️ Constructor](#constructor) (2 params)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [CollectionObject](#collectionobject) → `$CollectionObject : Object`
    - [SetIndex](#setindex) (1 param)
    - [GetIndex](#getindex) → `$index : Integer`
    - [SetPlaceholder](#setplaceholder) (1 param)
    - [AppendValue](#appendvalue) (1 param)
    - [AppendValueWithPrimaryKey](#appendvaluewithprimarykey) (2 params)
    - [AppendValueWithEntity](#appendvaluewithentity) (2 params)
    - [GetCurrentValue](#getcurrentvalue) → `$currentValue : Variant`
    - [GetCurrentPrimaryKey](#getcurrentprimarykey) → `$currentPrimaryKey : Integer`
    - [GetCurrentEntity](#getcurrententity) → `$currentEntity : 4D.Entity`

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `_CollectionObject` | `Object` | - | Internal object storing collection values, current index, and selected value |
| `_primaryKeys` | `Collection` | `[]` | Collection of primary keys corresponding to each value |
| `_entities` | `Collection` | `[]` | Collection of entity objects corresponding to each value |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($valuesCollection : Collection; $placeHolderText : Text)
```

Creates a collection wrapper for UI dropdowns with optional placeholder text

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$valuesCollection` | `Collection` | - | - |
| `$placeHolderText` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### CollectionObject {#collectionobject}


```4d
Function CollectionObject -> $CollectionObject : Object
```

Returns the internal collection object containing values, index, and currentValue

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
Function GetIndex -> $index : Integer
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
Function GetCurrentValue -> $currentValue : Variant
```

**Returns:** `Variant`

---

#### GetCurrentPrimaryKey {#getcurrentprimarykey}


```4d
Function GetCurrentPrimaryKey -> $currentPrimaryKey : Integer
```

**Returns:** `Integer`

---

#### GetCurrentEntity {#getcurrententity}


```4d
Function GetCurrentEntity -> $currentEntity : 4D.Entity
```

**Returns:** `4D.Entity`

---

---

*Generated from CollectionObject.4dm*
