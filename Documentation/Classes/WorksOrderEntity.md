---
layout : default
title : WorksOrderEntity
parent : Classes
---
# WorksOrderEntity

📊 **Overview:** 10 Functions | 6 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-13T21:44:56.616Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (10):**

- [setQuantityMade](#setquantitymade) (2 params) → `Date` 🖥️
- [getQuantityMade](#getquantitymade) (1 param) → `Integer` 🖥️
- [getQuantityPacked](#getquantitypacked) (1 param) → `Integer` 🖥️
- [getQuantityScrapped](#getquantityscrapped) → `Integer` 🖥️
- [query IsRunning](#query isrunning) (1 param) 🖥️
- [query IsOpen](#query isopen) (1 param) 🖥️
- [calculateProcessScrap](#calculateprocessscrap) (2 params) 🖥️
- [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
- [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
- [query HasMigrationID](#query hasmigrationid) (1 param) → `Text` 🖥️

**🔍 Getters (6):**

- [AvailableStock](#availablestock) → `Integer`
- [WIP](#wip) → `Integer`
- [IsRunning](#isrunning) → `Boolean`
- [IsOpen](#isopen) → `Boolean`
- [HasMigrationID](#hasmigrationid) → `Boolean`
- [ExS1Stock](#exs1stock) → `Integer`

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

#### setQuantityMade {#setquantitymade}
 `[🖥️ local]`

```4d
Function setQuantityMade($NewQuantity : Integer; $AdjustmentDate : Date) -> Date
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$NewQuantity` | `Integer` | - | - |
| `$AdjustmentDate` | `Date` | - | - |

**Returns:** `Date`

---

#### getQuantityMade {#getquantitymade}
 `[🖥️ local]`

```4d
Function getQuantityMade($UseRealTimeData : Boolean) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$UseRealTimeData` | `Boolean` | - | - |

**Returns:** `Integer`

---

#### getQuantityPacked {#getquantitypacked}
 `[🖥️ local]`

```4d
Function getQuantityPacked($InStockOnly : Boolean) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$InStockOnly` | `Boolean` | - | - |

**Returns:** `Integer`

---

#### getQuantityScrapped {#getquantityscrapped}
 `[🖥️ local]`

```4d
Function getQuantityScrapped -> Integer
```

**Returns:** `Integer`

---

#### query IsRunning {#query isrunning}
 `[🖥️ local]`

```4d
Function query IsRunning($QueryEventObject : Object)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

---

#### query IsOpen {#query isopen}
 `[🖥️ local]`

```4d
Function query IsOpen($QueryEventObject : Object)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

---

#### calculateProcessScrap {#calculateprocessscrap}
 `[🖥️ local]`

```4d
Function calculateProcessScrap($MachineCompleted : Boolean; $PackingCompleted : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MachineCompleted` | `Boolean` | - | - |
| `$PackingCompleted` | `Boolean` | - | - |

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.WorksOrderEntity) -> $Collection : Collection
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.WorksOrderEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.WorksOrderEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.WorksOrderEntity` | - | - |

---

#### query HasMigrationID {#query hasmigrationid}
 `[🖥️ local]`

```4d
Function query HasMigrationID($QueryEventObject : Object) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$QueryEventObject` | `Object` | - | - |

**Returns:** `Text`

---

### 🔍 Getters

#### AvailableStock {#availablestock}
 `[🖥️ local, 🔍 getter]`

```4d
Function AvailableStock -> Integer
```

**Returns:** `Integer`

---

#### WIP {#wip}
 `[🖥️ local, 🔍 getter]`

```4d
Function WIP -> Integer
```

**Returns:** `Integer`

---

#### IsRunning {#isrunning}
 `[🖥️ local, 🔍 getter]`

```4d
Function IsRunning -> Boolean
```

**Returns:** `Boolean`

---

#### IsOpen {#isopen}
 `[🖥️ local, 🔍 getter]`

```4d
Function IsOpen -> Boolean
```

**Returns:** `Boolean`

---

#### HasMigrationID {#hasmigrationid}
 `[🖥️ local, 🔍 getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

#### ExS1Stock {#exs1stock}
 `[🖥️ local, 🔍 getter]`

```4d
Function ExS1Stock -> Integer
```

**Returns:** `Integer`

---

## 🔗 Related Items

### 🗂️ Tables

- [WorksOrder](../Tables/WorksOrder.md) - Source table for this ORDA class
- [WorksOrder](../Tables/WorksOrder.md) - Database table storing WorksOrder records

### � Related Classes

- [WorksOrder](WorksOrder.md) - ORDA DataClass class for WorksOrder table
- [WorksOrderEntity](WorksOrderEntity.md) - ORDA Entity class for WorksOrder table

---

*Generated from WorksOrderEntity.4dm*
