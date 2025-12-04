---
layout : default
title : MachineMaintenanceActions
parent : Tables
---
# MachineMaintenanceActions

📊 **Overview:** 4 Fields | 1 Indexes | 2 One-to-Many Relations

## 📝 Description

🗨️ Master data table defining maintenance tasks and procedures for production equipment. Specifies required actions, frequencies, and checklists.

## ℹ️ Table Information

- **Table ID:** 113
- **UUID:** 3F67965E543B564DB573483EBEAC4C96
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:13Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Action | `String` (255) | - | - |
| Frequency | `Long Integer` | - | - |
| FrequencyType | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `MachineMaintenanceLogSelection` | [MachineMaintenanceLog](MachineMaintenanceLog.md) | `MachineMaintenanceActionID` → `ID` | Active | - |
| `MachineMaintenanceRequirementsSelection` | [MachineMaintenanceRequirements](MachineMaintenanceRequirements.md) | `MachineMaintenanceActionID` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [MachineMaintenance](../Forms/MachineMaintenance.md) - Data source for MachineMaintenance form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:13Z*
