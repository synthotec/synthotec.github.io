---
layout : default
title : WorksOrderEntity
parent : Classes
---
# WorksOrderEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/WorksOrderEntity.4dm)

📊 **Overview:** 7 Functions | 6 Getters

**Extends:** `Entity`

🕐 *Last updated: 2025-11-19T21:53:04.648Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setQuantityMade](#setquantitymade) (2 params) → `Date` 🖥️
    - [getQuantityMade](#getquantitymade) (1 param) → `Integer` 🖥️
    - [getQuantityPacked](#getquantitypacked) (1 param) → `Integer` 🖥️
    - [getQuantityScrapped](#getquantityscrapped) → `Integer` 🖥️
    - [calculateProcessScrap](#calculateprocessscrap) (2 params) 🖥️
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
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

### Computed Attributes (Getters/Setters/Query/OrderBy)

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

- [WorksOrder](../Tables/WorksOrder.md) - ORDA Entity class for WorksOrder table

### � Related Classes

- [WorksOrder](WorksOrder.md) - ORDA DataClass class for WorksOrder table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [%2AStockControl](../Forms/%2AStockControl.md) - Data source for %2AStockControl form
- [%2ATempOEE](../Forms/%2ATempOEE.md) - Data source for %2ATempOEE form
- [%2Atest](../Forms/%2Atest.md) - Data source for %2Atest form
- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form
- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [LabelHistory](../Forms/LabelHistory.md) - Data source for LabelHistory form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [MachineMaintenance](../Forms/MachineMaintenance.md) - Data source for MachineMaintenance form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [ProductStockTake](../Forms/ProductStockTake.md) - Data source for ProductStockTake form
- [Quality](../Forms/Quality.md) - Data source for Quality form
- [QualitySystemResults](../Forms/QualitySystemResults.md) - Data source for QualitySystemResults form
- [QuarantineManager](../Forms/QuarantineManager.md) - Data source for QuarantineManager form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [test](../Forms/test.md) - Data source for test form
- [WODateRange](../Forms/WODateRange.md) - Data source for WODateRange form
- [WorkInProgress](../Forms/WorkInProgress.md) - Data source for WorkInProgress form
- [WO_Numbers](../Forms/WO_Numbers.md) - Data source for WO_Numbers form

---

*Generated from WorksOrderEntity.4dm*
