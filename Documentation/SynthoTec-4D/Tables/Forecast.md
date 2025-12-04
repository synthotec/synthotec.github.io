---
layout : default
title : Forecast
parent : Tables
---
# Forecast

📊 **Overview:** 6 Fields | 3 Indexes | 1 Many-to-One Relations

## 📝 Description

🗨️ Planning table storing demand forecasts by product and period. Used for capacity planning and material requirement calculations.

## ℹ️ Table Information

- **Table ID:** 108
- **UUID:** 3D30ED9FCDC1D24697A8C1D1F6F01D55
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:08Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| ForecastYear | `Integer` | 🚫 Not Null | - |
| ForecastMonth | `Integer` | 🚫 Not Null | - |
| Quantity | `Long Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ProductID` | Keywords | regular | - |
| `ForecastYear` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Forecast](../Classes/Forecast.md) - ORDA DataClass class for Forecast table
- [ForecastEntity](../Classes/ForecastEntity.md) - ORDA Entity class for Forecast table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:08Z*
