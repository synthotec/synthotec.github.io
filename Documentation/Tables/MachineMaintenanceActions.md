---
layout : default
title : MachineMaintenanceActions
parent : Tables
---
# MachineMaintenanceActions

📊 **Overview:** 4 Fields | 1 Indexes | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 113
- **UUID:** 3F67965E543B564DB573483EBEAC4C96
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:36Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Action | `String` (255) | - | - |
| Frequency | `Date` | - | - |
| FrequencyType | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `MachineMaintenanceLogSelection` | [MachineMaintenanceLog](MachineMaintenanceLog.md) | `MachineMaintenanceActionID` → `ID` | Active | - |
| `MachineMaintenanceRequirementsSelection` | [MachineMaintenanceRequirements](MachineMaintenanceRequirements.md) | `MachineMaintenanceActionID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:36Z*
