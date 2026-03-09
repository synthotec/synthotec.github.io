---
layout : default
title : ForecastEntity
parent : Classes
---
# ForecastEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ForecastEntity.4dm)

📊 **Overview:** 1 Getters

## 📝 Description

Entity representing a monthly product forecast with a derived Consignment flag that checks whether a consignment product option exists for the forecasted product and customer combination.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.716Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [Consignment](#consignment) 🔍 → `Boolean`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### Consignment {#consignment}
 `[🔍 get only]`

```4d
Function get Consignment -> Boolean
```

Returns true if there is a consignment product option for this forecast's product and customer

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Forecast](../Tables/Forecast.md) - ORDA Entity class for Forecast table

### � Related Classes

- [Forecast](Forecast.md) - ORDA DataClass class for Forecast table

---

*Generated from ForecastEntity.4dm*
