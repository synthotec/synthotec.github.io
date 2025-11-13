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
- **Generated:** 🕐 2025-11-13T16:09:37Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| MigrationID | `Date` | - | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:09:37Z*
