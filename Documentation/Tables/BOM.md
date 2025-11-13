---
layout : default
title : BOM
parent : Tables
---
# BOM

📊 **Overview:** 42 Fields | 6 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 81
- **UUID:** 54265309B2FD8743A7314DCD2E8357C4
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:48:59Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (42)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Date` | 🚫 Not Null | - |
| Impressions | `Picture` | 🚫 Not Null | - |
| PartWeight | `Boolean` | 🚫 Not Null | - |
| RunnerWeight | `Boolean` | 🚫 Not Null | - |
| MaterialID | `Date` | 🚫 Not Null | - |
| RegrindWeight | `Boolean` | 🚫 Not Null | - |
| WasteFactor | `Boolean` | 🚫 Not Null | - |
| PackagingCost | `Boolean` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| MaterialValue | `Boolean` | 🚫 Not Null | - |
| SalesPrice | `Boolean` | 🚫 Not Null | - |
| PackingLabourCost | `Boolean` | 🚫 Not Null | - |
| TransportPrice | `Boolean` | 🚫 Not Null | - |
| PartCost | `Boolean` | 🚫 Not Null | - |
| RunnerCost | `Boolean` | 🚫 Not Null | - |
| RegrindValue | `Boolean` | 🚫 Not Null | - |
| WasteCost | `Boolean` | 🚫 Not Null | - |
| ForecastQty | `Date` | 🚫 Not Null | - |
| MaterialYieldLossCost | `Boolean` | 🚫 Not Null | - |
| MaterialYieldLossPercent | `Boolean` | 🚫 Not Null | - |
| EnergyCost | `Boolean` | 🚫 Not Null | - |
| Locked | `Real` | 🚫 Not Null | - |
| SnapShotDate | `Integer` | 🚫 Not Null | - |
| PartsPerHour | `Boolean` | 🚫 Not Null | - |
| PackagingMarginDeduction | `Boolean` | 🚫 Not Null | - |
| IndirectLabourCost | `Boolean` | 🚫 Not Null | - |
| RepairsCost | `Boolean` | 🚫 Not Null | - |
| DepreciationCost | `Boolean` | 🚫 Not Null | - |
| OverheadsCost | `Boolean` | 🚫 Not Null | - |
| PackingLabourTime | `Long Integer` | 🚫 Not Null | - |
| ClosedLoopPercentage | `Boolean` | 🚫 Not Null | - |
| OEE_Percentage | `Boolean` | 🚫 Not Null | - |
| SecondaryOverheadsCost | `Boolean` | 🚫 Not Null | - |
| AverageRunLength | `Date` | 🚫 Not Null | - |
| SetterCost | `Boolean` | - | - |
| CycleTime | `Boolean` | 🚫 Not Null | - |
| TotalMaterialValue | `Boolean` | 🚫 Not Null | - |
| TotalDirectCosts | `Boolean` | 🚫 Not Null | - |
| TotalFactoryCosts | `Boolean` | 🚫 Not Null | - |
| PackingLabourTime_Secs | `Boolean` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ProductID` | Keywords | regular | - |
| `Customer` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `MaterialID` | Keywords | regular | - |
| `Locked` | Keywords | regular | - |
| `SnapShotDate` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active | - |
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [BOM](../Classes/BOM.md) - DataClass class
- [BOMEntity](../Classes/BOMEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:59Z*
