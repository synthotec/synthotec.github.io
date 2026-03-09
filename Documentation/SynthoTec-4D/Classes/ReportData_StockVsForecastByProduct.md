---
layout : default
title : ReportData_StockVsForecastByProduct
parent : Classes
---
# ReportData_StockVsForecastByProduct [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData_StockVsForecastByProduct.4dm)

📊 **Overview:** 11 Properties | 1 Constructor | 11 Functions

## 📝 Description

Report dataset comparing current stock levels against forecast volumes by product. Supports configurable look-back periods, customer group filtering, remote S1 datastore data, and optional filtering to only products with a stock-to-forecast ratio below a threshold.

**Extends:** `ReportData`

🕐 *Last updated: 2026-03-09T14:45:31.455Z*

---

## 📑 Table of Contents

- [📋 Properties (11)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [mergeProductObjects](#mergeproductobjects)
    - [addToCollection](#addtocollection) (1 param)
    - [getTool_FirstRunDate](#gettool_firstrundate) (2 params) → `Date`
    - [getTool_LastRunDate](#gettool_lastrundate) (1 param) → `Date`
    - [getTool_VolumeProduced](#gettool_volumeproduced) (1 param) → `Integer`
    - [getTool_RunCount](#gettool_runcount) (1 param) → `Integer`
    - [getForecastVolume](#getforecastvolume) (1 param) → `Integer`
    - [preloadRemoteData](#preloadremotedata) (1 param)
    - [getTool_ProductionData](#gettool_productiondata) (1 param) → `$ResultObject : Object`
    - [getTool_ComplaintCount](#gettool_complaintcount) (1 param) → `Integer`
    - [getTool_PeakVolume](#gettool_peakvolume) (1 param) → `Object`
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `CustomerGroup` | `Text` | `"NSK"` | Customer group filter for querying forecasts (empty string = all customers) |
| `IncludeS1Data` | `Boolean` | `False` | When True, also includes works order and CofC data from the remote (S1) datastore |
| `Forecast_StartYear` | `Integer` | `Year of(Current date)` | First forecast year to sum when calculating ForecastVolume |
| `Forecast_EndYear` | `Integer` | `Year of(Current date)` | Last forecast year to sum when calculating ForecastVolume |
| `LookBackMonths` | `Integer` | `12` | Number of months to look back when calculating production and complaint statistics |
| `OnlyShowIfStockOrForecast` | `Boolean` | `False` | When True, excludes products with no stock and no forecast |
| `ProblemStockRatioPercent` | `Real` | `0` | When >0, only includes products whose stock-to-forecast ratio is below this threshold |
| `RemoteToolMap` | `Object` | `{}` | Maps local Tool_ID to remote Tool_ID for cross-datastore lookups |
| `RemoteWorksOrderCollection` | `Collection` | `[]` | Pre-fetched works order records from the remote datastore |
| `RemoteCofCCollection` | `Collection` | `[]` | Pre-fetched CofC records from the remote datastore |
| `RemoteNonConformanceCollection` | *Not specified* | `[]` | Pre-fetched non-conformance records from the remote datastore |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Parameters : Object)
```

Builds a per-product collection comparing current stock, forecast volume, and historical production metrics; optionally includes S1 remote data

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### mergeProductObjects {#mergeproductobjects}


```4d
Function mergeProductObjects
```

Merges child product rows into their parent product row and marks child rows for removal, combining all aggregate metrics

---

#### addToCollection {#addtocollection}


```4d
Function addToCollection($ProductObject : Object)
```

Applies filtering rules (OnlyShowIfStockOrForecast, ProblemStockRatioPercent) before pushing the product object into Collection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductObject` | `Object` | - | - |

---

#### getTool_FirstRunDate {#gettool_firstrundate}


```4d
Function getTool_FirstRunDate($ToolsEntity : cs.ToolsEntity; $RemoteToolsEntity : cs.ToolsEntity) -> Date
```

Returns the earliest qualifying works order start date for the tool across local and remote datastores

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |
| `$RemoteToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Date`

---

#### getTool_LastRunDate {#gettool_lastrundate}


```4d
Function getTool_LastRunDate($ToolsEntity : cs.ToolsEntity) -> Date
```

Returns the most recent qualifying works order start date for the tool across local and remote datastores

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Date`

---

#### getTool_VolumeProduced {#gettool_volumeproduced}


```4d
Function getTool_VolumeProduced($ToolsEntity : cs.ToolsEntity) -> Integer
```

Returns total quantity manufactured by this tool within the lookback period, combining local and remote data

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Integer`

---

#### getTool_RunCount {#gettool_runcount}


```4d
Function getTool_RunCount($ToolsEntity : cs.ToolsEntity) -> Integer
```

Returns the number of production runs for this tool within the lookback period, combining local and remote data

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Integer`

---

#### getForecastVolume {#getforecastvolume}


```4d
Function getForecastVolume($ProductEntity : cs.ProductEntity) -> Integer
```

Returns sum of forecast quantities for the product across the configured Forecast_StartYear to Forecast_EndYear range

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductEntity` | `cs.ProductEntity` | - | - |

**Returns:** `Integer`

---

#### preloadRemoteData {#preloadremotedata}


```4d
Function preloadRemoteData($LocalToolIDs : Collection)
```

Pre-fetches works order, CofC, and non-conformance data from the remote datastore for the given local tool IDs; skips if IncludeS1Data is False

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$LocalToolIDs` | `Collection` | - | - |

---

#### getTool_ProductionData {#gettool_productiondata}


```4d
Function getTool_ProductionData($ToolsEntity : cs.ToolsEntity) -> $ResultObject : Object
```

Returns an object with ProductionHours and UnplannedDowntimeHours for the tool within the lookback period

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Object`

---

#### getTool_ComplaintCount {#gettool_complaintcount}


```4d
Function getTool_ComplaintCount($ToolsEntity : cs.ToolsEntity) -> Integer
```

Returns the total complaint (non-conformance) count for this tool within the lookback period, combining local and remote data

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Integer`

---

#### getTool_PeakVolume {#gettool_peakvolume}


```4d
Function getTool_PeakVolume($ToolsEntity : cs.ToolsEntity) -> Object
```

Returns {Year, Volume} object representing the year with the highest annual delivery quantity for this tool across local and remote data

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `cs.ToolsEntity` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### � Related Classes

- [ReportData](ReportData.md) - Base class for ReportData_StockVsForecastByProduct

---

*Generated from ReportData_StockVsForecastByProduct.4dm*
