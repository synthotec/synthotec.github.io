---
layout : default
title : ExampleClass
parent : Classes
---
# ExampleClass

## Description

🗨️ Example class to demonstrate inline comments and parameter documentation

## Table of Contents

### Properties

- [Title](#title)
- [Count](#count)

### Functions

- [constructor() [constructor]](#constructor)
- [calculateValue()](#calculatevalue)
- [processOrder()](#processorder)
- [ItemCount() [getter]](#itemcount)

---

## Properties

### Title {#title}

**Type:** `Text`

---

### Count {#count}

**Type:** `Integer`

**Default Value:** `0`

---

## Functions

### constructor {#constructor}
 `[constructor]`

```4d
Class constructor($InitialCount : Integer)
```

$InitialCount: Starting inventory count

---

### calculateValue {#calculatevalue}


```4d
Function calculateValue($UnitPrice : Real) -> Real
```

Returns total inventory value

**Returns:** `Real`

---

### processOrder {#processorder}


```4d
Function processOrder($Quantity : Integer; $DiscountPercent : Real) -> Boolean
```

$Quantity: Number of items to order

**Returns:** `Boolean`

---

### ItemCount {#itemcount}
 `[getter]`

```4d
Function ItemCount -> Integer
```

**Returns:** `Integer`

---

---

*Generated from ExampleClass.4dm*
*Last updated: 2025-11-13T00:30:41.408Z*
