---
layout : default
title : Material
parent : Tables
---
# Material

📊 **Overview:** 26 Fields | 9 Indexes | 3 Many-to-One Relations | 11 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 11
- **UUID:** 13EE0980326D984887426E4CEDD50A30
- **Primary Key:** 🔑 `Unique_ID`
- **Generated:** 🕐 2025-11-13T23:17:51Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (26)
- [🔍 Indexes](#-indexes) (9)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (11)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (21)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Unique_ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null, ��� Not Modifiable | - |
| MaterialName | `String` (80) | 🚫 Not Null | - |
| Customers Name | `String` (35) | 🚫 Not Null | - |
| In Stock | `Date` | 🚫 Not Null | - |
| Supplier Code | `String` (3) | 🚫 Not Null | - |
| Supplier Name | `String` (25) | 🚫 Not Null | - |
| Current | `Real` | 🚫 Not Null | - |
| Short Name | `String` (35) | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |
| Colour_l | `Date` | 🚫 Not Null | - |
| Manufacturer_s | `String` (20) | 🚫 Not Null | - |
| UsageMatID | `Date` | 🚫 Not Null | - |
| SafetyStockTarget | `Picture` | 🚫 Not Null | - |
| BOM_Price | `Boolean` | 🚫 Not Null | - |
| LossPercent | `Boolean` | 🚫 Not Null | - |
| UsageMatID2 | `Date` | 🚫 Not Null | - |
| UsageMatID2Percent | `Boolean` | 🚫 Not Null | - |
| Calendar_Price | `Boolean` | 🚫 Not Null | - |
| UsageMatID3 | `Date` | 🚫 Not Null | - |
| UsageMatID3Percent | `Boolean` | 🚫 Not Null | - |
| FontColour | `Date` | 🚫 Not Null | - |
| BOM_Comment | `String` (255) | 🚫 Not Null | - |
| SharedMaterialSource | `Real` | 🚫 Not Null | - |
| LeadTimeDays | `Date` | - | - |
| MigrationID | `Date` | - | - |
| LastMigration | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `UsageMatID3` | Keywords | regular | - |
| `UsageMatID` | Keywords | regular | - |
| `Current` | Keywords | regular | - |
| `Archive` | Keywords | regular | - |
| `MigrationID` | Keywords | regular | - |
| `UsageMatID2` | Keywords | regular | - |
| `MaterialName` | Keywords | regular | - |
| `Unique_ID` | Keywords | regular | ✨ Yes |
| `Customers Name` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `UsageMat1Entity` | [Material](Material.md) | `UsageMatID` → `Unique_ID` | Active | - |
| `UsageMat2Entity` | [Material](Material.md) | `UsageMatID2` → `Unique_ID` | Active | - |
| `UsageMat3Entity` | [Material](Material.md) | `UsageMatID3` → `Unique_ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Material_ID` → `Unique_ID` | Active | - |
| `Product_OptionSelection` | [Product_Option](Product_Option.md) | `Material_ID` → `Unique_ID` | Active | - |
| `RMCSelection` | [RMC](RMC.md) | `MaterialID_l` → `Unique_ID` | Active | - |
| `WheelCalendarSelection` | [WheelCalendar](WheelCalendar.md) | `MatID` → `Unique_ID` | Active | - |
| `BOMSelection` | [BOM](BOM.md) | `MaterialID` → `Unique_ID` | Active | - |
| `MaterialCheckHistorySelection` | [MaterialCheckHistory](MaterialCheckHistory.md) | `MaterialID` → `Unique_ID` | Active | - |
| `PlanningWheelSelection` | [PlanningWheel](PlanningWheel.md) | `MaterialID` → `Unique_ID` | Active | - |
| `ProductMaterialOptionsSelection` | [ProductMaterialOptions](ProductMaterialOptions.md) | `MaterialID` → `Unique_ID` | Active | - |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `MaterialID` → `Unique_ID` | Active | - |
| `ProductSelection` | [Product](Product.md) | `DefMatID` → `Unique_ID` | Active | - |
| `WorksOrderSelection` | [WorksOrder](WorksOrder.md) | `MaterialID` → `Unique_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Material](../Classes/Material.md) - ORDA DataClass class for Material table
- [MaterialEntity](../Classes/MaterialEntity.md) - ORDA Entity class for Material table

### 📄 Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [%2AToolEditor](../Forms/%2AToolEditor.md) - Data source for %2AToolEditor form
- [BOM](../Forms/BOM.md) - Data source for BOM form
- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [BOM_Output](../Forms/BOM_Output.md) - Data source for BOM_Output form
- [BOM_Packaging](../Forms/BOM_Packaging.md) - Data source for BOM_Packaging form
- [ChangeMaterial](../Forms/ChangeMaterial.md) - Data source for ChangeMaterial form
- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [Materials](../Forms/Materials.md) - Data source for Materials form
- [NewScrapEntry](../Forms/NewScrapEntry.md) - Data source for NewScrapEntry form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [SupplyInfo](../Forms/SupplyInfo.md) - Data source for SupplyInfo form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:51Z*
