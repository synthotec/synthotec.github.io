---
layout : default
title : RTSUMSelection
parent : Classes
---
# RTSUMSelection [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RTSUMSelection.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

Entity selection of real-time summary records, providing a helper to calculate total material consumed in production (in kg) across the selection, with an option to subtract regrind weight from the calculation.

**Extends:** `EntitySelection`

🕐 *Last updated: 2026-03-09T14:45:31.529Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMaterialUsedForProduction](#getmaterialusedforproduction) (1 param) → `Real` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMaterialUsedForProduction {#getmaterialusedforproduction}
 `[🖥️ local]`

```4d
Function getMaterialUsedForProduction($subtractRegrind : Boolean) -> Real
```

Returns the total material used for production in kg, optionally excluding regrind weight

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$subtractRegrind` | `Boolean` | - | - |

**Returns:** `Real`

---

## Related Items {#related-items}

### 🗂️ Tables

- [RTSUM](../Tables/RTSUM.md) - ORDA EntitySelection class for RTSUM table

### � Related Classes

- [RTSUM](RTSUM.md) - ORDA DataClass class for RTSUM table

### � Forms

- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form

---

*Generated from RTSUMSelection.4dm*
