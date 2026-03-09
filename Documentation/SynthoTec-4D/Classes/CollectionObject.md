---
layout : default
title : CollectionObject
parent : Classes
---
# CollectionObject [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CollectionObject.4dm)

📊 **Overview:** 3 Properties | 1 Constructor | 10 Functions

## 📝 Description

Wrapper class that binds a 4D collection to a form dropdown widget, managing the selected index, current value, placeholder text, and optionally associated primary keys and entity references for each item.

🕐 *Last updated: 2026-03-09T14:45:29.182Z*

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

Sets the current selected index in the collection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$index` | `Integer` | - | - |

---

#### GetIndex {#getindex}


```4d
Function GetIndex -> $index : Integer
```

Returns the current selected index in the collection

**Returns:** `Integer`

---

#### SetPlaceholder {#setplaceholder}


```4d
Function SetPlaceholder($placeHolderText : Text)
```

Resets selection to placeholder state with specified text

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$placeHolderText` | `Text` | - | - |

---

#### AppendValue {#appendvalue}


```4d
Function AppendValue($value : Variant)
```

Adds a new value to the collection without primary key or entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$value` | `Variant` | - | - |

---

#### AppendValueWithPrimaryKey {#appendvaluewithprimarykey}


```4d
Function AppendValueWithPrimaryKey($value : Variant; $primaryKey : Integer)
```

Adds a new value to the collection with associated primary key

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

Adds a new value to the collection with associated entity reference

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

Returns the currently selected value from the collection

**Returns:** `Variant`

---

#### GetCurrentPrimaryKey {#getcurrentprimarykey}


```4d
Function GetCurrentPrimaryKey -> $currentPrimaryKey : Integer
```

Returns the primary key associated with the currently selected item

**Returns:** `Integer`

---

#### GetCurrentEntity {#getcurrententity}


```4d
Function GetCurrentEntity -> $currentEntity : 4D.Entity
```

Returns the entity associated with the currently selected item

**Returns:** `4D.Entity`

---

---

*Generated from CollectionObject.4dm*
