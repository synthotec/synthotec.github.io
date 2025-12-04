---
layout : default
title : SalesForecast
parent : Tables
---
# SalesForecast

📊 **Overview:** 22 Fields | 7 Indexes

## 📝 Description

🗨️ Planning table storing customer demand forecasts by product and period. Used for long-term capacity planning and inventory management.

## ℹ️ Table Information

- **Table ID:** 49
- **UUID:** 0412FF273154D14EA78AFDEC1CD85D3D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:12Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (22)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (7)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ProductID | `Long Integer` | 🚫 Not Null | - |
| fYear | `Integer` | 🚫 Not Null | - |
| January | `Integer` | 🚫 Not Null | - |
| February | `Integer` | 🚫 Not Null | - |
| March | `Integer` | 🚫 Not Null | - |
| April | `Integer` | 🚫 Not Null | - |
| May | `Integer` | 🚫 Not Null | - |
| June | `Integer` | 🚫 Not Null | - |
| July | `Integer` | 🚫 Not Null | - |
| August | `Integer` | 🚫 Not Null | - |
| September | `Integer` | 🚫 Not Null | - |
| October | `Integer` | 🚫 Not Null | - |
| November | `Integer` | 🚫 Not Null | - |
| December | `Integer` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| LastEdited | `Date` | 🚫 Not Null | - |
| YearlyVolume | `Integer` | 🚫 Not Null | - |
| SnapShot | `Boolean` | 🚫 Not Null | - |
| SnapDate | `Date` | 🚫 Not Null | - |
| CurrentBacklog | `Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `fYear` | Cluster | regular | - |
| `ProductID` | Cluster | regular | - |
| `SnapDate` | Cluster | regular | - |
| `Customer` | Cluster | regular | - |
| `PartName` | Cluster | regular | - |
| `SnapShot` | Cluster | regular | - |
| `ID` | B-Tree | regular | ✨ Yes |

## 🔗 Related Items

### 📄 Forms

- [BOM_CustomerTransport](../Forms/BOM_CustomerTransport.md) - Data source for BOM_CustomerTransport form
- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [BOM_Packaging](../Forms/BOM_Packaging.md) - Data source for BOM_Packaging form
- [CapacityPlanning](../Forms/CapacityPlanning.md) - Data source for CapacityPlanning form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [ForecastImporter](../Forms/ForecastImporter.md) - Data source for ForecastImporter form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:12Z*
