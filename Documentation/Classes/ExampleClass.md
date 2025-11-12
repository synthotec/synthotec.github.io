# ExampleClass

## Description

Example class to demonstrate inline comments and parameter documentation

## Table of Contents

### Properties

- [Title](#title)
- [Count](#count)

### Functions

- [calculateValue()](#calculatevalue)
- [processOrder()](#processorder)
- [ItemCount() [getter]](#itemcount)

---

## Properties

### Title {#title}

**Type:** `Text`

The title of the item

---

### Count {#count}

**Type:** `Integer`

**Default Value:** `0`

Number of items in stock

---

## Functions

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
*Last updated: 2025-11-12T17:04:21.681Z*
