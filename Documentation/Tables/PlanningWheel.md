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
- **Generated:** 🕐 2025-11-13T02:35:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (34)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### TargetQty

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### PeriodStart

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### PeriodFinish

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### StartDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### HoursOfProduction

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### FinishDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ActualQty

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### RunOrder

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Machine

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### StartDaysEarly

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### FinishDaysEarly

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### PartName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### OnlyForecast

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### FixedRun

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Tool

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### SetDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### 🔑 WheelID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### DailyPlannedHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Late

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AvgCycle

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Trial

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Notes

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Impressions

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Conflict

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### TargetQtyThousands

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Changed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ConflictReason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MaterialConflict

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### InitialYear

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### BalancingQuantity

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolID` | Keywords | regular | - |
| `Tool` | Keywords | regular | - |
| `ProductID` | Keywords | regular | - |
| `Conflict` | Cluster | regular | - |
| `WheelID` | Keywords | regular | ✨ Yes |
| `Machine` | Cluster | regular | - |
| `MaterialConflict` | Keywords | regular | - |

### Detailed Information

- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Tool`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Conflict`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `WheelID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `MaterialConflict`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active |
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |

### Detailed Information

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:49Z*
