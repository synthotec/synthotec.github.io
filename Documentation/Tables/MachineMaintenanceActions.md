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
- **Generated:** 🕐 2025-11-13T02:36:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Action | `String` (255) | - | - |
| Frequency | `Date` | - | - |
| FrequencyType | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Action

**Properties:**

- **Type:** String (max length: 255)

---

#### Frequency

**Properties:**

- **Type:** Date

---

#### FrequencyType

**Properties:**

- **Type:** Date

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

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `MachineMaintenanceLogSelection` | [MachineMaintenanceLog](MachineMaintenanceLog.md) | `MachineMaintenanceActionID` → `ID` | Active |
| `MachineMaintenanceRequirementsSelection` | [MachineMaintenanceRequirements](MachineMaintenanceRequirements.md) | `MachineMaintenanceActionID` → `ID` | Active |

### Detailed Information

#### MachineMaintenanceLogSelection

**Links from:** [MachineMaintenanceLog](MachineMaintenanceLog.md)

- **Source Table:** `MachineMaintenanceLog`
- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** Active

---

#### MachineMaintenanceRequirementsSelection

**Links from:** [MachineMaintenanceRequirements](MachineMaintenanceRequirements.md)

- **Source Table:** `MachineMaintenanceRequirements`
- **Source Field:** `MachineMaintenanceActionID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:45Z*
