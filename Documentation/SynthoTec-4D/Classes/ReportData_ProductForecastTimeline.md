---
layout : default
title : ReportData_ProductForecastTimeline
parent : Classes
---
# ReportData_ProductForecastTimeline [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData_ProductForecastTimeline.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 3 Functions

## 📝 Description

Report dataset showing per-product yearly sales actuals alongside quarterly 2026 forecast snapshots. Supports customer group filtering, optional S1 remote datastore data inclusion, and volume conversion from units to machine hours via PartsPerHour.

**Extends:** `ReportData`

🕐 *Last updated: 2026-03-09T14:45:31.287Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getSales](#getsales) (2 params) → `Integer`
    - [preloadRemoteData](#preloadremotedata) (1 param)
    - [getForecast](#getforecast) (3 params) → `Integer`
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `CustomerGroup` | `Text` | `"NSK"` | Customer group filter for querying forecast products (empty string = all customers) |
| `IncludeS1Data` | `Boolean` | `True` | When True, includes historical sales from the remote (S1) datastore |
| `DisplayVolumeAs` | `Text` | `"UNITS"` | Output unit: "UNITS" for part quantities or "HOURS" to convert using PartsPerHour |
| `RemoteProductMap` | `Object` | - | Maps local Product_ID to remote Product_ID for cross-datastore lookups |
| `RemoteCofCData` | `Collection` | - | Pre-fetched CofC records from the remote datastore |
| `ConvertToHours` | `Boolean` | - | Derived from DisplayVolumeAs; True when volumes should be shown as machine hours |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Parameters : Object)
```

Builds a per-product collection with yearly sales actuals and quarterly 2026 forecast snapshots; optionally includes S1 remote data

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### getSales {#getsales}


```4d
Function getSales($ProductEntity : cs.ProductEntity; $SalesYear : Integer) -> Integer
```

Returns total delivered quantity for the product in the given year, combining local CofC and remote CofC if IncludeS1Data is True

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductEntity` | `cs.ProductEntity` | - | - |
| `$SalesYear` | `Integer` | - | - |

**Returns:** `Integer`

---

#### preloadRemoteData {#preloadremotedata}


```4d
Function preloadRemoteData($ForecastSelection : cs.ForecastSelection)
```

Builds RemoteProductMap and pre-fetches RemoteCofCData from the remote datastore for all products in the forecast selection

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ForecastSelection` | `cs.ForecastSelection` | - | - |

---

#### getForecast {#getforecast}


```4d
Function getForecast($ProductEntity : cs.ProductEntity; $ForecastYear : Integer; $SnapshotDate : Date) -> Integer
```

Returns the forecast yearly volume for a product, optionally filtered to a specific snapshot date

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductEntity` | `cs.ProductEntity` | - | - |
| `$ForecastYear` | `Integer` | - | - |
| `$SnapshotDate` | `Date` | - | - |

**Returns:** `Integer`

---

## Related Items {#related-items}

### � Related Classes

- [ReportData](ReportData.md) - Base class for ReportData_ProductForecastTimeline

---

*Generated from ReportData_ProductForecastTimeline.4dm*
