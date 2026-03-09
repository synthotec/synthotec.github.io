---
layout : default
title : RTSUM
parent : Classes
---
# RTSUM [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RTSUM.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for real-time production summary records, aggregating cycle-level data into daily machine/works order summaries for reporting. Provides generation across a date range and optional works order filter.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.524Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [generate](#generate) (3 params) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### generate {#generate}
 `[🖥️ local]`

```4d
Function generate($StartDate : Date; $EndDate : Date; $SelectedWorksOrder : Integer)
```

Generates real-time summary records for specified date range and works orders

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StartDate` | `Date` | - | - |
| `$EndDate` | `Date` | - | - |
| `$SelectedWorksOrder` | `Integer` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [RTSUM](../Tables/RTSUM.md) - ORDA DataClass class for RTSUM table

### � Related Classes

- [RTSUMSelection](RTSUMSelection.md) - ORDA EntitySelection class for RTSUM table

### � Forms

- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form

---

*Generated from RTSUM.4dm*
