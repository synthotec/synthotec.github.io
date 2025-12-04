---
layout : default
title : WheelCalendar
parent : Tables
---
# WheelCalendar

📊 **Overview:** 24 Fields | 10 Indexes | 3 Many-to-One Relations

## 📝 Description

🗨️ Calendar table mapping time periods to planning wheel positions. Defines date-to-wheel-position relationships for visual scheduling.

## ℹ️ Table Information

- **Table ID:** 51
- **UUID:** DE47E38D9F06C94798575B35E1D1A5C3
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:14Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (24)
- [🔍 Indexes](#-indexes) (10)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Machine | `Integer` | 🚫 Not Null | - |
| MCDate | `Date` | 🚫 Not Null | - |
| Hours | `Real` | 🚫 Not Null | - |
| RegrindAmountKg | `Real` | 🚫 Not Null | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| MatID | `Long Integer` | 🚫 Not Null | - |
| MatAmountKG | `Real` | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| Parts | `Long Integer` | 🚫 Not Null | - |
| ToolChange | `Boolean` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| ToolNumber | `String` (255) | 🚫 Not Null | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| DateReq | `Date` | 🚫 Not Null | - |
| TotalQty | `Long Integer` | 🚫 Not Null | - |
| SetDate | `Date` | 🚫 Not Null | - |
| WheelID | `Long Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| HasSetDate | `Boolean` | 🚫 Not Null | - |
| RemainingHours | `Real` | 🚫 Not Null | - |
| Trial | `Boolean` | 🚫 Not Null | - |
| ToolID | `Long Integer` | 🚫 Not Null | - |
| ChangeDate | `Date` | 🚫 Not Null | - |

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

## 🔗 Related Items

### 📄 Forms

- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:14Z*
