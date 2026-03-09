---
layout : default
title : Product_Option
parent : Classes
---
# Product_Option [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Product_Option.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for product option records, defining specific combinations of product, tool, material, and customer that form a priced production option. Supports entity migration (linking disabled).

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.870Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns migration configuration disabling entity linking for Product_Option

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Product_Option](../Tables/Product_Option.md) - ORDA DataClass class for Product_Option table

### � Related Classes

- [Product_OptionEntity](Product_OptionEntity.md) - ORDA Entity class for Product_Option table

### � Forms

- [BOM](../Forms/BOM.md) - Data source for BOM form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form

---

*Generated from Product_Option.4dm*
