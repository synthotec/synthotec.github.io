---
layout : default
title : WorksOrderEntity
parent : Classes
---
# WorksOrderEntity [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/WorksOrderEntity.4dm)

📊 **Overview:** 7 Functions | 6 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-14T16:35:59.651Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - [setQuantityMade](#setquantitymade) (2 params) → `Date` 🖥️
  - [getQuantityMade](#getquantitymade) (1 param) → `Integer` 🖥️
  - [getQuantityPacked](#getquantitypacked) (1 param) → `Integer` 🖥️
  - [getQuantityScrapped](#getquantityscrapped) → `Integer` 🖥️
  - [IsRunning](#isrunning) (1 param) 🖥️
  - [IsOpen](#isopen) (1 param) 🖥️
  - [calculateProcessScrap](#calculateprocessscrap) (2 params) 🖥️
  - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
  - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - [HasMigrationID](#hasmigrationid) (1 param) → `Text` 🖥️
  - [AvailableStock](#availablestock) 🔍 → `Integer`
  - [ExS1Stock](#exs1stock) 🔍 → `Integer`
  - [HasMigrationID](#hasmigrationid) 🔍 🔎 → `Boolean`
  - [IsOpen](#isopen) 🔍 🔎 → `Boolean`
  - [IsRunning](#isrunning) 🔍 🔎 → `Boolean`
  - [WIP](#wip) 🔍 → `Integer`
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

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

### Properties (Getters/Setters/Query/OrderBy)

#### AvailableStock {#availablestock}
 `[🔍 get only, 🖥️ local]`

```4d
Function get AvailableStock -> Integer
```

**Returns:** `Integer`

---

#### ExS1Stock {#exs1stock}
 `[🔍 get only, 🖥️ local]`

```4d
Function get ExS1Stock -> Integer
```

**Returns:** `Integer`

---

#### HasMigrationID {#hasmigrationid}
 `[🔍 get, 🔎 query, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
Function query HasMigrationID($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

**Returns:** `Boolean`

---

#### IsOpen {#isopen}
 `[🔍 get, 🔎 query, 🖥️ local]`

```4d
Function get IsOpen -> Boolean
Function query IsOpen($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

**Returns:** `Boolean`

---

#### IsRunning {#isrunning}
 `[🔍 get, 🔎 query, 🖥️ local]`

```4d
Function get IsRunning -> Boolean
Function query IsRunning($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

**Returns:** `Boolean`

---

#### WIP {#wip}
 `[🔍 get only, 🖥️ local]`

```4d
Function get WIP -> Integer
```

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [WorksOrder](../Tables/WorksOrder.md) - Source table for this ORDA class

### � Related Classes

- [WorksOrder](WorksOrder.md) - ORDA DataClass class for WorksOrder table

---

*Generated from WorksOrderEntity.4dm*
