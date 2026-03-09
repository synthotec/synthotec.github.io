---
layout : default
title : ReportData_ProductSopAnalysis
parent : Classes
---
# ReportData_ProductSopAnalysis [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData_ProductSopAnalysis.4dm)

📊 **Overview:** 6 Properties | 1 Constructor | 3 Functions

## 📝 Description

Report dataset analysing start-of-production dates and tool lifetime volumes for products within a customer group (default NSK). Combines local and remote datastore works order and forecast data to calculate per-product yearly volumes and production age for SOP timeline reporting.

**Extends:** `ReportData`

🕐 *Last updated: 2026-03-09T14:45:31.327Z*

---

## 📑 Table of Contents

- [📋 Properties (6)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [processMaps](#processmaps)
    - [getLocalData](#getlocaldata) (1 param) → `Collection`
    - [getRemoteData](#getremotedata) (1 param) → `Collection`
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `CustomerGroup` | *Not specified* | `"NSK"` | Customer group filter used when querying Forecast and CofC records |
| `StartYear` | *Not specified* | `2021` | Earliest year included in the analysis |
| `EndYear` | *Not specified* | `2026` | Latest year included in the analysis |
| `Local` | *Not specified* | `{\` | - |
| `Remote` | *Not specified* | `{\` | - |
| `RemoteProductIDs` | *Not specified* | `[]` | Product IDs from the remote datastore used for cross-referencing with local products |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($_ : Object)
```

Builds the SOP analysis by pre-fetching forecast, CofC, works-order, and product data from both local and remote datastores, then merging into a per-product yearly volume map

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$_` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### processMaps {#processmaps}


```4d
Function processMaps
```

Merges local and remote product maps into Collection, calculating start dates and adding year columns for sales/forecast volumes

---

#### getLocalData {#getlocaldata}


```4d
Function getLocalData($CustomerCodes : Collection) -> Collection
```

Pre-fetches forecast, CofC, product, tools, and works order data from the local datastore into the Local context object

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CustomerCodes` | `Collection` | - | - |

**Returns:** `Collection`

---

#### getRemoteData {#getremotedata}


```4d
Function getRemoteData($CustomerCodes : Collection) -> Collection
```

Pre-fetches forecast, CofC, product, tools, and works order data from the remote (S1) datastore into the Remote context object

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CustomerCodes` | `Collection` | - | - |

**Returns:** `Collection`

---

## Related Items {#related-items}

### � Related Classes

- [ReportData](ReportData.md) - Base class for ReportData_ProductSopAnalysis

---

*Generated from ReportData_ProductSopAnalysis.4dm*
