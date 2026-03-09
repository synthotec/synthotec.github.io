---
layout : default
title : Forecast
parent : Classes
---
# Forecast [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Forecast.4dm)

📊 **Overview:** 2 Functions

## 📝 Description

DataClass for pre-calculated monthly forecast records. Regenerates the forecast table by truncating it and rebuilding from active SalesForecast snapshot records, used to power reporting and procurement planning.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:29.711Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [generate](#generate) → `$Success : Boolean` 🖥️
    - [generateForecastOrders](#generateforecastorders) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### generate {#generate}
 `[🖥️ local]`

```4d
Function generate -> $Success : Boolean
```

Generates forecast data by truncating table and creating monthly forecast entities from SalesForecast records

**Returns:** `Boolean`

---

#### generateForecastOrders {#generateforecastorders}
 `[🖥️ local]`

```4d
Function generateForecastOrders
```

Creates forecast customer orders for each non-zero forecast quantity from current month through last forecast year

---

## Related Items {#related-items}

### 🗂️ Tables

- [Forecast](../Tables/Forecast.md) - ORDA DataClass class for Forecast table

### � Related Classes

- [ForecastEntity](ForecastEntity.md) - ORDA Entity class for Forecast table

---

*Generated from Forecast.4dm*
