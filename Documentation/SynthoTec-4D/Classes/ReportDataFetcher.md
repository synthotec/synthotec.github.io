---
layout : default
title : ReportDataFetcher
parent : Classes
---
# ReportDataFetcher [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportDataFetcher.4dm)

📊 **Overview:** 6 Functions

## 📝 Description

Singleton providing date, time, and datetime formatting helper functions for use by ReportData subclasses when serialising values for Power Query consumption (dates as ISO strings, times as HH:MM:SS, datetimes with timezone offset).

🕐 *Last updated: 2026-03-09T14:45:31.205Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [_date](#_date) (1 param) → `Text`
    - [_time](#_time) (1 param) → `Text`
    - [_datetime](#_datetime) (2 params) → `Text`
    - [Test](#test) (1 param) → `$Collection : Collection`
    - [ProductForecastOverview](#productforecastoverview) (1 param) → `$Collection : Collection`
    - [RealtimeTest](#realtimetest) (1 param) → `$Collection : Collection`

---

## Functions {#functions}

### Regular Functions

#### _date {#_date}


```4d
Function _date($Date : Date) -> Text
```

Return date as days since 1899-12-30 (Excel epoch)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Date` | `Date` | - | - |

**Returns:** `Text`

---

#### _time {#_time}


```4d
Function _time($Time : Time) -> Text
```

Return time as seconds since midnight

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Time` | `Time` | - | - |

**Returns:** `Text`

---

#### _datetime {#_datetime}


```4d
Function _datetime($Date : Date; $Time : Time) -> Text
```

Return datetime as days since 1899-12-30 plus fractional time

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Date` | `Date` | - | - |
| `$Time` | `Time` | - | - |

**Returns:** `Text`

---

#### Test {#test}


```4d
Function Test($Parameters : Object) -> $Collection : Collection
```

Test report returning sample data rows with index, name, amount, date, time, and datetime columns

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

**Returns:** `Collection`

---

#### ProductForecastOverview {#productforecastoverview}


```4d
Function ProductForecastOverview($Parameters : Object) -> $Collection : Collection
```

Returns per-product/customer 2026 forecast overview collection for the given customer group

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

**Returns:** `Collection`

---

#### RealtimeTest {#realtimetest}


```4d
Function RealtimeTest($Parameters : Object) -> $Collection : Collection
```

Placeholder report function returning empty collection; intended for real-time data testing

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

**Returns:** `Collection`

---

---

*Generated from ReportDataFetcher.4dm*
