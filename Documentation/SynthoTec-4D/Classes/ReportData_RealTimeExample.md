---
layout : default
title : ReportData_RealTimeExample
parent : Classes
---
# ReportData_RealTimeExample [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ReportData_RealTimeExample.4dm)

📊 **Overview:** 1 Properties | 1 Constructor

## 📝 Description

Report dataset providing machine stoppage events from the RealTime table on or after a configurable StartDate. Used as an example/reference implementation for RealTime-based Power Query data sources.

**Extends:** `ReportData`

🕐 *Last updated: 2026-03-09T14:45:31.339Z*

---

## 📑 Table of Contents

- [📋 Properties (1)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [🔗 Related Items](#related-items)


---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `StartDate` | `Date` | `Current date` | Earliest date for RealTime stoppage records to include |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($Parameters : Object)
```

Populates Collection with machine stoppage events from the RealTime table on or after StartDate

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Parameters` | `Object` | - | - |

---

## Related Items {#related-items}

### � Related Classes

- [ReportData](ReportData.md) - Base class for ReportData_RealTimeExample

---

*Generated from ReportData_RealTimeExample.4dm*
