---
layout : default
title : MachineMaintenanceRequirements
parent : Tables
---
# MachineMaintenanceRequirements

📊 **Overview:** 4 Fields | 1 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 114
- **UUID:** 45A9294EBF7DC04CB9F45F557F9377F7
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:35Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| MachineMaintenanceActionID | `Date` | - | - |
| Machine | `Date` | - | - |
| Required | `Real` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MachineMaintenanceActionsEntity` | [MachineMaintenanceActions](MachineMaintenanceActions.md) | `MachineMaintenanceActionID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:35Z*
