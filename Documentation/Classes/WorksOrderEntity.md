---
layout : default
title : WorksOrderEntity
parent : Classes
---
# WorksOrderEntity

**Extends:** `Entity`

## Table of Contents

### Functions

- [AvailableStock() [getter]](#availablestock)
- [setQuantityMade()](#setquantitymade)
- [getQuantityMade()](#getquantitymade)
- [getQuantityPacked()](#getquantitypacked)
- [getQuantityScrapped()](#getquantityscrapped)
- [WIP() [getter]](#wip)
- [IsRunning() [getter]](#isrunning)
- [query IsRunning()](#query isrunning)
- [IsOpen() [getter]](#isopen)
- [query IsOpen()](#query isopen)
- [calculateProcessScrap()](#calculateprocessscrap)
- [getMigrationRules()](#getmigrationrules)
- [syncMigrationSelections()](#syncmigrationselections)
- [HasMigrationID() [getter]](#hasmigrationid)
- [query HasMigrationID()](#query hasmigrationid)
- [ExS1Stock() [getter]](#exs1stock)

---

## Functions

### AvailableStock {#availablestock}
 `[local]` `[getter]`

```4d
Function AvailableStock -> Integer
```

**Returns:** `Integer`

---

### setQuantityMade {#setquantitymade}
 `[local]`

```4d
Function setQuantityMade($NewQuantity : Integer; $AdjustmentDate : Date) -> Date
```

**Returns:** `Date`

---

### getQuantityMade {#getquantitymade}
 `[local]`

```4d
Function getQuantityMade($UseRealTimeData : Boolean) -> Integer
```

**Returns:** `Integer`

---

### getQuantityPacked {#getquantitypacked}
 `[local]`

```4d
Function getQuantityPacked($InStockOnly : Boolean) -> Integer
```

**Returns:** `Integer`

---

### getQuantityScrapped {#getquantityscrapped}
 `[local]`

```4d
Function getQuantityScrapped -> Integer
```

**Returns:** `Integer`

---

### WIP {#wip}
 `[local]` `[getter]`

```4d
Function WIP -> Integer
```

**Returns:** `Integer`

---

### IsRunning {#isrunning}
 `[local]` `[getter]`

```4d
Function IsRunning -> Boolean
```

**Returns:** `Boolean`

---

### query IsRunning {#query isrunning}
 `[local]`

```4d
Function query IsRunning($QueryEventObject : Object)
```

---

### IsOpen {#isopen}
 `[local]` `[getter]`

```4d
Function IsOpen -> Boolean
```

**Returns:** `Boolean`

---

### query IsOpen {#query isopen}
 `[local]`

```4d
Function query IsOpen($QueryEventObject : Object)
```

---

### calculateProcessScrap {#calculateprocessscrap}
 `[local]`

```4d
Function calculateProcessScrap($MachineCompleted : Boolean; $PackingCompleted : Boolean)
```

---

### getMigrationRules {#getmigrationrules}
 `[local]`

```4d
Function getMigrationRules($RemoteEntity : cs.WorksOrderEntity) -> Collection
```

**Returns:** `Collection`

---

### syncMigrationSelections {#syncmigrationselections}
 `[local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.WorksOrderEntity)
```

---

### HasMigrationID {#hasmigrationid}
 `[local]` `[getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

### query HasMigrationID {#query hasmigrationid}
 `[local]`

```4d
Function query HasMigrationID($QueryEventObject : Object) -> Text
```

**Returns:** `Text`

---

### ExS1Stock {#exs1stock}
 `[local]` `[getter]`

```4d
Function ExS1Stock -> Integer
```

**Returns:** `Integer`

---

---

*Generated from WorksOrderEntity.4dm*
*Last updated: 2025-11-13T00:30:43.216Z*
