---
layout : default
title : Supplies
parent : Classes
---
# Supplies [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Supplies.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for consumable supply records (packaging materials, bags, boxes, etc.) used in production and despatch. Supports entity migration (linking disabled).

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:31.719Z*

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

Returns migration settings for the Supplies data class with linking disabled

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Supplies](../Tables/Supplies.md) - ORDA DataClass class for Supplies table

### � Related Classes

- [SuppliesEntity](SuppliesEntity.md) - ORDA Entity class for Supplies table

### � Forms

- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [BOM_Packaging](../Forms/BOM_Packaging.md) - Data source for BOM_Packaging form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [SupplyInfo](../Forms/SupplyInfo.md) - Data source for SupplyInfo form
- [TransferSupply](../Forms/TransferSupply.md) - Data source for TransferSupply form

---

*Generated from Supplies.4dm*
