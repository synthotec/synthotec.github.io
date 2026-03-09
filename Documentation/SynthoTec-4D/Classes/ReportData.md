---
layout : default
title : ReportData
parent : Classes
---
# ReportData [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData.4dm)

📊 **Overview:** 11 Properties | 1 Constructor | 4 Functions

## 📝 Description

Base class for Power Query-compatible report datasets. Subclasses populate the Collection property with row objects and define ColumnDefinitions for typed columns. Used to serve structured data to Power BI and Excel via REST endpoints.

🕐 *Last updated: 2026-03-09T14:45:31.193Z*

---

## 📑 Table of Contents

- [📋 Properties (11)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [_Date](#_date) (1 param) → `Text`
    - [_Time](#_time) (1 param) → `Text`
    - [_DateTime](#_datetime) (2 params) → `Text`
    - [getResultObject](#getresultobject) → `Object`
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Collection` | `Collection` | `[]` | Accumulated row objects that form the report dataset |
| `ColumnDefinitions` | `Object` | - | Maps column names to their data type strings (e.g., {Name: "text", Amount: "double"}) |
| `Type_Date` | *Not specified* | `"date"` | Column type constant for date values |
| `Type_Time` | *Not specified* | `"time"` | Column type constant for time values |
| `Type_DateTime` | *Not specified* | `"datetime"` | Column type constant for datetime values |
| `Type_DateTimezone` | *Not specified* | `"datetimezone"` | Column type constant for datetime values with timezone offset |
| `Type_Logical` | *Not specified* | `"logical"` | Boolean |
| `Type_Record` | *Not specified* | `"record"` | Object |
| `Type_Double` | *Not specified* | `"double"` | Real |
| `Type_Int64` | *Not specified* | `"int64"` | Column type constant for 64-bit integer values |
| `Type_Text` | *Not specified* | `"text"` | Column type constant for text values |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Parameters : Object)
```

Copies all properties from the Parameters object onto this instance, allowing subclasses to receive configuration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

---

## Functions {#functions}

### Regular Functions

#### _Date {#_date}


```4d
Function _Date($Date : Date) -> Text
```

Formats a date as an ISO 8601 date string (YYYY-MM-DD) suitable for report output

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Date` | `Date` | - | - |

**Returns:** `Text`

---

#### _Time {#_time}


```4d
Function _Time($Time : Time) -> Text
```

Formats a time as HH:MM:SS string suitable for report output

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Time` | `Time` | - | - |

**Returns:** `Text`

---

#### _DateTime {#_datetime}


```4d
Function _DateTime($Date : Date; $Time : Time) -> Text
```

Formats a date and time as an ISO 8601 datetime string with GMT offset

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Date` | `Date` | - | - |
| `$Time` | `Time` | - | - |

**Returns:** `Text`

---

#### getResultObject {#getresultobject}


```4d
Function getResultObject -> Object
```

Returns an object with Collection and ColumnDefinitions, ready to be sent as a REST response

**Returns:** `Object`

---

## Related Items {#related-items}

### � Related Classes

- [ReportData_CustomerVolumeAnalysis](ReportData_CustomerVolumeAnalysis.md) - Base class for ReportData_CustomerVolumeAnalysis
- [ReportData_OrdaQuery](ReportData_OrdaQuery.md) - Base class for ReportData_OrdaQuery
- [ReportData_ProductForecastTimeline](ReportData_ProductForecastTimeline.md) - Base class for ReportData_ProductForecastTimeline
- [ReportData_ProductSopAnalysis](ReportData_ProductSopAnalysis.md) - Base class for ReportData_ProductSopAnalysis
- [ReportData_RealTimeExample](ReportData_RealTimeExample.md) - Base class for ReportData_RealTimeExample
- [ReportData_RealTimeGantt](ReportData_RealTimeGantt.md) - Base class for ReportData_RealTimeGantt
- [ReportData_StockVsForecastByProduct](ReportData_StockVsForecastByProduct.md) - Base class for ReportData_StockVsForecastByProduct

---

*Generated from ReportData.4dm*
