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
- **Generated:** 🕐 2025-11-13T02:36:46Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| MachineMaintenanceActionID | `Date` | - | - |
| Machine | `Date` | - | - |
| Required | `Real` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### MachineMaintenanceActionID

**Properties:**

- **Type:** Date

---

#### Machine

**Properties:**

- **Type:** Date

---

#### Required

**Properties:**

- **Type:** Real

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `MachineMaintenanceActionsEntity` | [MachineMaintenanceActions](MachineMaintenanceActions.md) | `MachineMaintenanceActionID` → `ID` | Active |

### Detailed Information

#### MachineMaintenanceActionsEntity

**Links to:** [MachineMaintenanceActions](MachineMaintenanceActions.md)

- **Source Field:** `MachineMaintenanceActionID`
- **Destination Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:46Z*
