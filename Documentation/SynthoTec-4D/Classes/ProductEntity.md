---
layout : default
title : ProductEntity
parent : Classes
---
# ProductEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductEntity.4dm)

📊 **Overview:** 11 Functions | 3 Getters | 1 Setters

**Extends:** `Entity`

🕐 *Last updated: 2025-12-10T11:45:23.956Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getRobotHeadList](#getrobotheadlist) (1 param) → `Text` 🖥️
    - [getMainTool](#getmaintool) → `cs.ToolsEntity` 🖥️
    - [getPreviousPickRequestQuantity](#getpreviouspickrequestquantity) (2 params) → `Integer` 🖥️
    - [getFinishedStock](#getfinishedstock) → `Integer` 🖥️
    - [getQuarantinedStock](#getquarantinedstock) → `Integer` 🖥️
    - [getWIP](#getwip) → `Integer` 🖥️
    - [getPlannedProduction](#getplannedproduction) (1 param) → `Integer` 🖥️
    - [getPickRequestedQuantity](#getpickrequestedquantity) → `Integer` 🖥️
    - [getAvailableStock](#getavailablestock) (2 params) → `Integer` 🖥️
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Emoji](#emoji) 🔍 → `Text`
    - [HasMigrationID](#hasmigrationid) 🔍 → `Boolean`
    - [MainToolRegrind](#maintoolregrind) 🔍 ✏️ → `Boolean`
    - [OurPartName](#ourpartname) 🔎
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getRobotHeadList {#getrobotheadlist}
 `[🖥️ local]`

```4d
Function getRobotHeadList($Machine : Integer) -> Text
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Machine` | `Integer` | - | - |

**Returns:** `Text`

---

#### getMainTool {#getmaintool}
 `[🖥️ local]`

```4d
Function getMainTool -> cs.ToolsEntity
```

**Returns:** `cs.ToolsEntity`

---

#### getPreviousPickRequestQuantity {#getpreviouspickrequestquantity}
 `[🖥️ local]`

```4d
Function getPreviousPickRequestQuantity($PickRequestEntity : cs.PickRequestEntity; $OrderPickRequestEntity : cs.OrderPickRequestEntity) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |
| `$OrderPickRequestEntity` | `cs.OrderPickRequestEntity` | - | - |

**Returns:** `Integer`

---

#### getFinishedStock {#getfinishedstock}
 `[🖥️ local]`

```4d
Function getFinishedStock -> Integer
```

**Returns:** `Integer`

---

#### getQuarantinedStock {#getquarantinedstock}
 `[🖥️ local]`

```4d
Function getQuarantinedStock -> Integer
```

**Returns:** `Integer`

---

#### getWIP {#getwip}
 `[🖥️ local]`

```4d
Function getWIP -> Integer
```

**Returns:** `Integer`

---

#### getPlannedProduction {#getplannedproduction}
 `[🖥️ local]`

```4d
Function getPlannedProduction($DespatchDate : Date) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DespatchDate` | `Date` | - | - |

**Returns:** `Integer`

---

#### getPickRequestedQuantity {#getpickrequestedquantity}
 `[🖥️ local]`

```4d
Function getPickRequestedQuantity -> Integer
```

**Returns:** `Integer`

---

#### getAvailableStock {#getavailablestock}
 `[🖥️ local]`

```4d
Function getAvailableStock($PickRequestEntity : cs.PickRequestEntity; $OrderPickRequestEntity : cs.OrderPickRequestEntity) -> Integer
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PickRequestEntity` | `cs.PickRequestEntity` | - | - |
| `$OrderPickRequestEntity` | `cs.OrderPickRequestEntity` | - | - |

**Returns:** `Integer`

---

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.ProductEntity) -> $Collection : Collection
```

/////////////////////////////////////////////////////////////////////////////////////

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.ProductEntity)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.ProductEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Emoji {#emoji}
 `[🔍 get only, 🖥️ local]`

```4d
Function get Emoji -> Text
```

**Returns:** `Text`

---

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

#### MainToolRegrind {#maintoolregrind}
 `[🔍 get, ✏️ set, 🖥️ local]`

```4d
Function get MainToolRegrind -> Boolean
Function set MainToolRegrind($MainToolRegrind : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$MainToolRegrind` | `Boolean` | - |

**Returns:** `Boolean`

---

#### OurPartName {#ourpartname}
 `[🔎 query only, 🖥️ local]`

```4d
Function query OurPartName($QueryEventObject : Object)
```

**Query Function:** Enables querying this property in ORDA query strings (e.g., `.query(":1"; $Value)` where :1 is the property name).

**Query Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$QueryEventObject` | `Object` | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [Product](../Tables/Product.md) - ORDA Entity class for Product table

### � Related Classes

- [Product](Product.md) - ORDA DataClass class for Product table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [%2AStockControl](../Forms/%2AStockControl.md) - Data source for %2AStockControl form
- [%2Atest1](../Forms/%2Atest1.md) - Data source for %2Atest1 form
- [%2AToolEditor](../Forms/%2AToolEditor.md) - Data source for %2AToolEditor form
- [BOM](../Forms/BOM.md) - Data source for BOM form
- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [BOM_Output](../Forms/BOM_Output.md) - Data source for BOM_Output form
- [BOM_Packaging](../Forms/BOM_Packaging.md) - Data source for BOM_Packaging form
- [CapacityPlanning](../Forms/CapacityPlanning.md) - Data source for CapacityPlanning form
- [ChangeMaterial](../Forms/ChangeMaterial.md) - Data source for ChangeMaterial form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [EDIgenerator](../Forms/EDIgenerator.md) - Data source for EDIgenerator form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [ForecastImporter](../Forms/ForecastImporter.md) - Data source for ForecastImporter form
- [LabelPrinting](../Forms/LabelPrinting.md) - Data source for LabelPrinting form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [NSKPalletIDs](../Forms/NSKPalletIDs.md) - Data source for NSKPalletIDs form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [PackingLabour](../Forms/PackingLabour.md) - Data source for PackingLabour form
- [PalletTransfer](../Forms/PalletTransfer.md) - Data source for PalletTransfer form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [ProductStockTake](../Forms/ProductStockTake.md) - Data source for ProductStockTake form
- [QualitySystemResults](../Forms/QualitySystemResults.md) - Data source for QualitySystemResults form
- [QualitySystemTolerances](../Forms/QualitySystemTolerances.md) - Data source for QualitySystemTolerances form
- [QuarantineManager](../Forms/QuarantineManager.md) - Data source for QuarantineManager form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form
- [StockAtLocation](../Forms/StockAtLocation.md) - Data source for StockAtLocation form
- [ToolDisplay4](../Forms/ToolDisplay4.md) - Data source for ToolDisplay4 form
- [ToolStandardsReview](../Forms/ToolStandardsReview.md) - Data source for ToolStandardsReview form
- [WarehouseOptions](../Forms/WarehouseOptions.md) - Data source for WarehouseOptions form

---

*Generated from ProductEntity.4dm*
