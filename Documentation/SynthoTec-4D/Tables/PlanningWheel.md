---
layout : default
title : PlanningWheel
parent : Tables
---
# PlanningWheel

📊 **Overview:** 34 Fields | 7 Indexes | 2 Many-to-One Relations

## 📝 Description

🗨️ Visual scheduling master table defining planning wheel configurations. Manages circular schedule layouts showing machine assignments over time.

## ℹ️ Table Information

- **Table ID:** 50
- **UUID:** 210A450720703645BB31F7B5A4075752
- **Primary Key:** 🔑 `WheelID`
- **Generated:** 🕐 2025-12-04T14:34:13Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (34)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ProductID | `Long Integer` | 🚫 Not Null | - |
| TargetQty | `Integer` | 🚫 Not Null | - |
| PeriodStart | `Date` | 🚫 Not Null | - |
| PeriodFinish | `Date` | 🚫 Not Null | - |
| StartDate | `Date` | 🚫 Not Null | - |
| HoursOfProduction | `Real` | 🚫 Not Null | - |
| FinishDate | `Date` | 🚫 Not Null | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| ActualQty | `Integer` | 🚫 Not Null | - |
| RunOrder | `Real` | 🚫 Not Null | - |
| Machine | `Integer` | 🚫 Not Null | - |
| StartDaysEarly | `Real` | 🚫 Not Null | - |
| FinishDaysEarly | `Real` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| OnlyForecast | `Boolean` | 🚫 Not Null | - |
| FixedRun | `Boolean` | 🚫 Not Null | - |
| Tool | `String` (255) | 🚫 Not Null | - |
| SetDate | `Date` | 🚫 Not Null | - |
| 🔑 **WheelID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| DailyPlannedHours | `Real` | 🚫 Not Null | - |
| Late | `Boolean` | 🚫 Not Null | - |
| AvgCycle | `Real` | 🚫 Not Null | - |
| Trial | `Boolean` | 🚫 Not Null | - |
| Notes | `String` (255) | 🚫 Not Null | - |
| ToolID | `Long Integer` | 🚫 Not Null | - |
| Impressions | `Integer` | 🚫 Not Null | - |
| Conflict | `Boolean` | 🚫 Not Null | - |
| TargetQtyThousands | `Real` | 🚫 Not Null | - |
| Changed | `Boolean` | 🚫 Not Null | - |
| ConflictReason | `String` (255) | 🚫 Not Null | - |
| MaterialConflict | `Boolean` | 🚫 Not Null | - |
| MaterialID | `Long Integer` | 🚫 Not Null | - |
| InitialYear | `Integer` | 🚫 Not Null | - |
| BalancingQuantity | `Boolean` | 🚫 Not Null | - |

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

### 📄 Forms

- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [MaterialOptions](../Forms/MaterialOptions.md) - Data source for MaterialOptions form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:13Z*
