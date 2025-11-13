---
layout : default
title : CollectionObject
parent : Classes
---
# CollectionObject

## Table of Contents

### Functions

- [constructor() [constructor]](#constructor)
- [CollectionObject()](#collectionobject)
- [SetIndex()](#setindex)
- [GetIndex()](#getindex)
- [SetPlaceholder()](#setplaceholder)
- [AppendValue()](#appendvalue)
- [AppendValueWithPrimaryKey()](#appendvaluewithprimarykey)
- [AppendValueWithEntity()](#appendvaluewithentity)
- [GetCurrentValue()](#getcurrentvalue)
- [GetCurrentPrimaryKey()](#getcurrentprimarykey)
- [GetCurrentEntity()](#getcurrententity)

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($valuesCollection : Collection; $placeHolderText : Text)
```

---

### CollectionObject {#collectionobject}


```4d
Function CollectionObject -> Object
```

**Returns:** `Object`

---

### SetIndex {#setindex}


```4d
Function SetIndex($index : Integer)
```

---

### GetIndex {#getindex}


```4d
Function GetIndex -> Integer
```

**Returns:** `Integer`

---

### SetPlaceholder {#setplaceholder}


```4d
Function SetPlaceholder($placeHolderText : Text)
```

---

### AppendValue {#appendvalue}


```4d
Function AppendValue($value : Variant)
```

---

### AppendValueWithPrimaryKey {#appendvaluewithprimarykey}


```4d
Function AppendValueWithPrimaryKey($value : Variant; $primaryKey : Integer)
```

---

### AppendValueWithEntity {#appendvaluewithentity}


```4d
Function AppendValueWithEntity($value : Variant; $entity : 4D.Entity)
```

---

### GetCurrentValue {#getcurrentvalue}


```4d
Function GetCurrentValue -> Variant
```

**Returns:** `Variant`

---

### GetCurrentPrimaryKey {#getcurrentprimarykey}


```4d
Function GetCurrentPrimaryKey -> Integer
```

**Returns:** `Integer`

---

### GetCurrentEntity {#getcurrententity}


```4d
Function GetCurrentEntity -> 4D.Entity
```

**Returns:** `4D.Entity`

---

---

*Generated from CollectionObject.4dm*
*Last updated: 2025-11-13T00:30:41.029Z*
