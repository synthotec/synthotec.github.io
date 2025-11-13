---
layout : default
title : MachineMaintenanceLog
parent : Tables
---
# MachineMaintenanceLog

📊 **Overview:** 7 Fields | 1 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 112
- **UUID:** FE5239933752004A898745F680742B25
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:09:29Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Machine | `Date` | - | - |
| MachineMaintenanceActionID | `Date` | - | - |
| MaintenanceDate | `Integer` | - | - |
| MaintenanceTime | `Long Integer` | - | - |
| CompletedBy | `String` (255) | - | - |
| Comments | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MachineMaintenanceActionsEntity` | [MachineMaintenanceActions](MachineMaintenanceActions.md) | `MachineMaintenanceActionID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [MachineMaintenanceLogEntity](../Classes/MachineMaintenanceLogEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:09:29Z*
