---
layout : default
title : ToolTemperatureTarget
parent : Tables
---
# ToolTemperatureTarget

📊 **Overview:** 9 Fields | 3 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 119
- **UUID:** FE2D9E448CE7164B82091770BB81AD24
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:25:02Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (3)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Long Integer` | - | - |
| ZoneID | `Long Integer` | - | - |
| Target | `Real` | - | - |
| Min | `Real` | - | - |
| Max | `Real` | - | - |
| StaffID | `Long Integer` | - | - |
| LastUpdated | `String` (255) | - | - |
| MigrationID | `Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolID` | Keywords | regular | - |
| `ZoneID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active | - |
| `ToolTemperatureZoneEntity` | [ToolTemperatureZone](ToolTemperatureZone.md) | `ZoneID` → `ID` | Active | - |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ToolTemperatureTarget](../Classes/ToolTemperatureTarget.md) - ORDA DataClass class for ToolTemperatureTarget table
- [ToolTemperatureTargetEntity](../Classes/ToolTemperatureTargetEntity.md) - ORDA Entity class for ToolTemperatureTarget table
- [ToolTemperatureTargetSelection](../Classes/ToolTemperatureTargetSelection.md) - ORDA EntitySelection class for ToolTemperatureTarget table

### 📄 Forms

- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:25:02Z*
