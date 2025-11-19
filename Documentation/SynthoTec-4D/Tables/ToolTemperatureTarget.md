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
- **Generated:** 🕐 2025-11-13T23:19:41Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Date` | - | - |
| ZoneID | `Date` | - | - |
| Target | `Boolean` | - | - |
| Min | `Boolean` | - | - |
| Max | `Boolean` | - | - |
| StaffID | `Date` | - | - |
| LastUpdated | `String` (255) | - | - |
| MigrationID | `Undefined` | - | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:41Z*
