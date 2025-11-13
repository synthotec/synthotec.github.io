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
- **Generated:** 🕐 2025-11-13T02:47:50Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (29)
- [🔍 Indexes](#-indexes) (8)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product ID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Part No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Tool ID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Tool No | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Material_ID | `Date` | 🚫 Not Null | - |
| Material Name | `String` (80) | 🚫 Not Null | - |
| Price | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Customer Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Modified_Date | `Integer` | 🚫 Not Null | - |
| Currency | `String` (2) | 🚫 Not Null | - |
| INCOTERM | `String` (255) | 🚫 Not Null | - |
| Batch Quantity | `Date` | 🚫 Not Null | - |
| PriceQuantity | `Date` | 🚫 Not Null | - |
| DeliveryCost | `Boolean` | 🚫 Not Null | - |
| Comments | `String` | 🚫 Not Null | - |
| Consignment | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| ConsignmentMin | `Date` | 🚫 Not Null | - |
| ConsignmentMax | `Date` | 🚫 Not Null | - |
| CustomerReference | `String` (255) | 🚫 Not Null | - |
| Deconsigned_Stock | `Date` | 🚫 Not Null | - |
| CurrentConsignmentOrder | `String` (255) | 🚫 Not Null | - |
| Con_LastReceived | `Integer` | 🚫 Not Null | - |
| MOQ | `Date` | 🚫 Not Null | - |
| DefaultOrderNumber | `String` (255) | 🚫 Not Null | - |
| MOV | `Boolean` | 🚫 Not Null | - |
| SSLOffsetDays | `Picture` | - | - |
| SSLOverride | `Date` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:47:50Z*
