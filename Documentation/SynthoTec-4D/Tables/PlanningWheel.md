---
layout : default
title : PlanningWheel
parent : Tables
---
# PlanningWheel

📊 **Overview:** 34 Fields | 7 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 50
- **UUID:** 210A450720703645BB31F7B5A4075752
- **Primary Key:** 🔑 `WheelID`
- **Generated:** 🕐 2025-11-13T23:18:27Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (34)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ProductID | `Date` | 🚫 Not Null | - |
| TargetQty | `Undefined` | 🚫 Not Null | - |
| PeriodStart | `Integer` | 🚫 Not Null | - |
| PeriodFinish | `Integer` | 🚫 Not Null | - |
| StartDate | `Integer` | 🚫 Not Null | - |
| HoursOfProduction | `Boolean` | 🚫 Not Null | - |
| FinishDate | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| ActualQty | `Undefined` | 🚫 Not Null | - |
| RunOrder | `Boolean` | 🚫 Not Null | - |
| Machine | `Picture` | 🚫 Not Null | - |
| StartDaysEarly | `Boolean` | 🚫 Not Null | - |
| FinishDaysEarly | `Boolean` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| OnlyForecast | `Real` | 🚫 Not Null | - |
| FixedRun | `Real` | 🚫 Not Null | - |
| Tool | `String` (255) | 🚫 Not Null | - |
| SetDate | `Integer` | 🚫 Not Null | - |
| 🔑 **WheelID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| DailyPlannedHours | `Boolean` | 🚫 Not Null | - |
| Late | `Real` | 🚫 Not Null | - |
| AvgCycle | `Boolean` | 🚫 Not Null | - |
| Trial | `Real` | 🚫 Not Null | - |
| Notes | `String` (255) | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| Impressions | `Picture` | 🚫 Not Null | - |
| Conflict | `Real` | 🚫 Not Null | - |
| TargetQtyThousands | `Boolean` | 🚫 Not Null | - |
| Changed | `Real` | 🚫 Not Null | - |
| ConflictReason | `String` (255) | 🚫 Not Null | - |
| MaterialConflict | `Real` | 🚫 Not Null | - |
| MaterialID | `Date` | 🚫 Not Null | - |
| InitialYear | `Picture` | 🚫 Not Null | - |
| BalancingQuantity | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolID` | Keywords | regular | - |
| `Tool` | Keywords | regular | - |
| `ProductID` | Keywords | regular | - |
| `Conflict` | Cluster | regular | - |
| `WheelID` | Keywords | regular | ✨ Yes |
| `Machine` | Cluster | regular | - |
| `MaterialConflict` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active | - |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [PlanningWheel](../Classes/PlanningWheel.md) - ORDA DataClass class for PlanningWheel table
- [PlanningWheelEntity](../Classes/PlanningWheelEntity.md) - ORDA Entity class for PlanningWheel table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:27Z*
