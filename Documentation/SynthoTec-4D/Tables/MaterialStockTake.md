---
layout : default
title : MaterialStockTake
parent : Tables
---
# MaterialStockTake

📊 **Overview:** 12 Fields | 4 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 53
- **UUID:** A38A78E19EE7594CADD598417056C9D4
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:30Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (5)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| StockTakeDate | `Integer` | 🚫 Not Null | - |
| RMC | `Date` | 🚫 Not Null | - |
| MatID | `Picture` | 🚫 Not Null | - |
| Bags | `Boolean` | 🚫 Not Null | - |
| AmountKG | `Boolean` | 🚫 Not Null | - |
| RMCID | `Date` | 🚫 Not Null | - |
| MaterialName | `String` (255) | 🚫 Not Null | - |
| Location | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| CountedBy | `String` (255) | 🚫 Not Null | - |
| PrimaryStockTake | `Real` | 🚫 Not Null | - |
| SavedTimeStamp | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `MatID` | Keywords | regular | - |
| `StockTakeDate` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `PrimaryStockTake` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `RMCEntity` | [RMC](RMC.md) | `RMC` → `RMCNo_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [MaterialStockTake](../Classes/MaterialStockTake.md) - ORDA DataClass class for MaterialStockTake table

### 📄 Forms

- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:30Z*
