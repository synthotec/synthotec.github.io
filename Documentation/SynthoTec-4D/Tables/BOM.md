---
layout : default
title : BOM
parent : Tables
---
# BOM

📊 **Overview:** 42 Fields | 6 Indexes | 3 Many-to-One Relations

## 📝 Description

🗨️ Test manual comment for BOM table

## ℹ️ Table Information

- **Table ID:** 81
- **UUID:** 54265309B2FD8743A7314DCD2E8357C4
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:43Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (42)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| Impressions | `Integer` | 🚫 Not Null | - |
| PartWeight | `Real` | 🚫 Not Null | - |
| RunnerWeight | `Real` | 🚫 Not Null | - |
| MaterialID | `Long Integer` | 🚫 Not Null | - |
| RegrindWeight | `Real` | 🚫 Not Null | - |
| WasteFactor | `Real` | 🚫 Not Null | - |
| PackagingCost | `Real` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| MaterialValue | `Real` | 🚫 Not Null | - |
| SalesPrice | `Real` | 🚫 Not Null | - |
| PackingLabourCost | `Real` | 🚫 Not Null | - |
| TransportPrice | `Real` | 🚫 Not Null | - |
| PartCost | `Real` | 🚫 Not Null | - |
| RunnerCost | `Real` | 🚫 Not Null | - |
| RegrindValue | `Real` | 🚫 Not Null | - |
| WasteCost | `Real` | 🚫 Not Null | - |
| ForecastQty | `Long Integer` | 🚫 Not Null | - |
| MaterialYieldLossCost | `Real` | 🚫 Not Null | - |
| MaterialYieldLossPercent | `Real` | 🚫 Not Null | - |
| EnergyCost | `Real` | 🚫 Not Null | - |
| Locked | `Boolean` | 🚫 Not Null | - |
| SnapShotDate | `Date` | 🚫 Not Null | - |
| PartsPerHour | `Real` | 🚫 Not Null | - |
| PackagingMarginDeduction | `Real` | 🚫 Not Null | - |
| IndirectLabourCost | `Real` | 🚫 Not Null | - |
| RepairsCost | `Real` | 🚫 Not Null | - |
| DepreciationCost | `Real` | 🚫 Not Null | - |
| OverheadsCost | `Real` | 🚫 Not Null | - |
| PackingLabourTime | `Time` | 🚫 Not Null | - |
| ClosedLoopPercentage | `Real` | 🚫 Not Null | - |
| OEE_Percentage | `Real` | 🚫 Not Null | - |
| SecondaryOverheadsCost | `Real` | 🚫 Not Null | - |
| AverageRunLength | `Long Integer` | 🚫 Not Null | - |
| SetterCost | `Real` | - | - |
| CycleTime | `Real` | 🚫 Not Null | - |
| TotalMaterialValue | `Real` | 🚫 Not Null | - |
| TotalDirectCosts | `Real` | 🚫 Not Null | - |
| TotalFactoryCosts | `Real` | 🚫 Not Null | - |
| PackingLabourTime_Secs | `Real` | 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

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

- [BOM](../Classes/BOM.md) - ORDA DataClass class for BOM table
- [BOMEntity](../Classes/BOMEntity.md) - ORDA Entity class for BOM table

### 📄 Forms

- [BOM](../Forms/BOM.md) - Data source for BOM form
- [BOM_Output](../Forms/BOM_Output.md) - Data source for BOM_Output form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:43Z*
