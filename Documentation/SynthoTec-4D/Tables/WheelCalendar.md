---
layout : default
title : WheelCalendar
parent : Tables
---
# WheelCalendar

📊 **Overview:** 24 Fields | 10 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 51
- **UUID:** DE47E38D9F06C94798575B35E1D1A5C3
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:28Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (24)
- [🔍 Indexes](#-indexes) (10)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Machine | `Picture` | 🚫 Not Null | - |
| MCDate | `Integer` | 🚫 Not Null | - |
| Hours | `Boolean` | 🚫 Not Null | - |
| RegrindAmountKg | `Boolean` | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| MatID | `Date` | 🚫 Not Null | - |
| MatAmountKG | `Boolean` | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| Parts | `Date` | 🚫 Not Null | - |
| ToolChange | `Real` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| ToolNumber | `String` (255) | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| DateReq | `Integer` | 🚫 Not Null | - |
| TotalQty | `Date` | 🚫 Not Null | - |
| SetDate | `Integer` | 🚫 Not Null | - |
| WheelID | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| HasSetDate | `Real` | 🚫 Not Null | - |
| RemainingHours | `Boolean` | 🚫 Not Null | - |
| Trial | `Real` | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| ChangeDate | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ProductID` | Keywords | regular | - |
| `MatID` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `Machine` | Cluster | regular | - |
| `PartName` | Cluster | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `MCDate` | Keywords | regular | - |
| `ToolChange` | Cluster | regular | - |
| `WheelID` | Cluster | regular | - |
| `ToolID` | Cluster | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MaterialEntity` | [Material](Material.md) | `MatID` → `Unique_ID` | Active | - |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:28Z*
