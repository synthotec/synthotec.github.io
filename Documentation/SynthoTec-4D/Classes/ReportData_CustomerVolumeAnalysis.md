---
layout : default
title : ReportData_CustomerVolumeAnalysis
parent : Classes
---
# ReportData_CustomerVolumeAnalysis [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData_CustomerVolumeAnalysis.4dm)

📊 **Overview:** 10 Properties | 1 Constructor | 7 Functions

## 📝 Description

Report dataset aggregating product volumes and values for a customer group across a selected year. Can use forecast quantities for the current or future year, and optionally pulls Certificate of Conformance actuals and product/tool details from both local and remote (S1) datastores.

**Extends:** `ReportData`

🕐 *Last updated: 2026-03-09T14:45:31.240Z*

---

## 📑 Table of Contents

- [📋 Properties (10)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [prefetchPhase1RemoteData](#prefetchphase1remotedata)
    - [prefetchPhase2SelectiveData](#prefetchphase2selectivedata)
    - [processMappedValues](#processmappedvalues)
    - [getProductPricePerPart](#getproductpriceperpart) (2 params) → `Real`
    - [getToolFirstRunDate](#gettoolfirstrundate) (2 params) → `Date`
    - [mapCofCSelection](#mapcofcselection) (2 params)
    - [mapForecastSelection](#mapforecastselection) (1 param)
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `CustomerGroup` | `Text` | `"NSK"` | Customer group filter used when querying customers (e.g., "NSK") |
| `Year` | `Integer` | `2021` | Year of(Current date) |
| `UseForecast` | `Boolean` | - | True when Year is current or future year; uses forecast quantities instead of CofC actuals |
| `ProductIDQuantityMap` | `Object` | `{}` | Maps product ID strings to {Volume, Value} objects accumulated across all customers |
| `RemoteCustomerCollection` | `Collection` | - | Pre-fetched customer records from remote datastore for ID matching |
| `RemoteCofCCollection` | `Collection` | - | Pre-fetched CofC records from remote datastore for the selected year |
| `RemoteProductCollection` | `Collection` | - | Pre-fetched product records from remote datastore |
| `RemoteToolsCollection` | `Collection` | - | Pre-fetched main tool records from remote datastore |
| `RemoteWorksOrderCollection` | `Collection` | - | Pre-fetched works order records from remote datastore |
| `CurrencyObject` | *Not specified* | `New object("£"; 0.87; "€"; 1)` | Maps currency symbols to EUR conversion rates for value calculations |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($_ : Object)
```

Builds a per-product report for a customer group and year, mapping either forecast or CofC quantities and computing value/machine hour metrics

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$_` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### prefetchPhase1RemoteData {#prefetchphase1remotedata}


```4d
Function prefetchPhase1RemoteData
```

Phase 1: Pre-fetch remote customers and CofC (only when not using forecast)

---

#### prefetchPhase2SelectiveData {#prefetchphase2selectivedata}


```4d
Function prefetchPhase2SelectiveData
```

Phase 2: Selective pre-fetch of only the remote products/tools that will be used

---

#### processMappedValues {#processmappedvalues}


```4d
Function processMappedValues
```

Iterates ProductIDQuantityMap, resolves product and tool details, then pushes formatted objects into Collection

---

#### getProductPricePerPart {#getproductpriceperpart}


```4d
Function getProductPricePerPart($ProductID : Integer; $Remote : Boolean) -> Real
```

Returns the per-part price in EUR for a product, applying currency conversion via CurrencyObject

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductID` | `Integer` | - | - |
| `$Remote` | `Boolean` | - | - |

**Returns:** `Real`

---

#### getToolFirstRunDate {#gettoolfirstrundate}


```4d
Function getToolFirstRunDate($ToolsEntity : Object; $Remote : Boolean) -> Date
```

Returns the earliest qualifying works order start date for the tool, checking both local and remote data

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ToolsEntity` | `Object` | - | - |
| `$Remote` | `Boolean` | - | - |

**Returns:** `Date`

---

#### mapCofCSelection {#mapcofcselection}


```4d
Function mapCofCSelection($CustomerEntity : Object; $Remote : Boolean)
```

Accumulates delivery quantities from CofC records for a customer into ProductIDQuantityMap, using negative IDs for remote products

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CustomerEntity` | `Object` | - | - |
| `$Remote` | `Boolean` | - | - |

---

#### mapForecastSelection {#mapforecastselection}


```4d
Function mapForecastSelection($CustomerEntity : cs.CustomerEntity)
```

Accumulates forecast quantities for the configured Year from a customer's ForecastSelection into ProductIDQuantityMap

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CustomerEntity` | `cs.CustomerEntity` | - | - |

---

## Related Items {#related-items}

### � Related Classes

- [ReportData](ReportData.md) - Base class for ReportData_CustomerVolumeAnalysis

---

*Generated from ReportData_CustomerVolumeAnalysis.4dm*
