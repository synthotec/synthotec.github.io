---
layout : default
title : ToolTemperatureZone
parent : Tables
---
# ToolTemperatureZone

📊 **Overview:** 3 Fields | 1 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 120
- **UUID:** 968EE478343D5B48862979641CF58B28
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:25:03Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| MigrationID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `ZoneID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ToolTemperatureZone](../Classes/ToolTemperatureZone.md) - ORDA DataClass class for ToolTemperatureZone table
- [ToolTemperatureZoneEntity](../Classes/ToolTemperatureZoneEntity.md) - ORDA Entity class for ToolTemperatureZone table

### 📄 Forms

- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:25:03Z*
