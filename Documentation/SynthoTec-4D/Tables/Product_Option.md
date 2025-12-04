---
layout : default
title : Product_Option
parent : Tables
---
# Product_Option

📊 **Overview:** 29 Fields | 8 Indexes | 4 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 13
- **UUID:** 2E835762FEA7484EB4687878631CFB10
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:28Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (29)
- [🔍 Indexes](#-indexes) (8)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (9)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product ID | `Long Integer` | ⚠️ Required, 🚫 Not Null | - |
| Part No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Tool ID | `Long Integer` | ⚠️ Required, 🚫 Not Null | - |
| Tool No | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Material_ID | `Long Integer` | 🚫 Not Null | - |
| Material Name | `String` (80) | 🚫 Not Null | - |
| Price | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Customer Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Modified_Date | `Date` | 🚫 Not Null | - |
| Currency | `String` (2) | 🚫 Not Null | - |
| INCOTERM | `String` (255) | 🚫 Not Null | - |
| Batch Quantity | `Long Integer` | 🚫 Not Null | - |
| PriceQuantity | `Long Integer` | 🚫 Not Null | - |
| DeliveryCost | `Real` | 🚫 Not Null | - |
| Comments | `String` | 🚫 Not Null | - |
| Consignment | `Boolean` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| ConsignmentMin | `Long Integer` | 🚫 Not Null | - |
| ConsignmentMax | `Long Integer` | 🚫 Not Null | - |
| CustomerReference | `String` (255) | 🚫 Not Null | - |
| Deconsigned_Stock | `Long Integer` | 🚫 Not Null | - |
| CurrentConsignmentOrder | `String` (255) | 🚫 Not Null | - |
| Con_LastReceived | `Date` | 🚫 Not Null | - |
| MOQ | `Long Integer` | 🚫 Not Null | - |
| DefaultOrderNumber | `String` (255) | 🚫 Not Null | - |
| MOV | `Real` | 🚫 Not Null | - |
| SSLOffsetDays | `Integer` | - | - |
| SSLOverride | `Long Integer` | 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Material Name` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Part No` | Keywords | regular | - |
| `Price` | Keywords | regular | - |
| `Product ID` | Keywords | regular | - |
| `Tool No` | Keywords | regular | - |
| `Customer Code` | Keywords | regular | - |
| `Material_ID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `Product ID` → `Product_ID` | Active | - |
| `MaterialEntity` | [Material](Material.md) | `Material_ID` → `Unique_ID` | Active | - |
| `CustomerEntity` | [Customer](Customer.md) | `Customer Code` → `Customer_Code` | Active | - |
| `ToolsEntity` | [Tools](Tools.md) | `Tool ID` → `Tool_ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Product_OptionID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Product_Option](../Classes/Product_Option.md) - ORDA DataClass class for Product_Option table
- [Product_OptionEntity](../Classes/Product_OptionEntity.md) - ORDA Entity class for Product_Option table

### 📄 Forms

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

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:28Z*
