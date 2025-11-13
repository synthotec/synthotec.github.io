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
- **Generated:** 🕐 2025-11-13T02:36:44Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Machine | `Date` | - | - |
| MachineMaintenanceActionID | `Date` | - | - |
| MaintenanceDate | `Integer` | - | - |
| MaintenanceTime | `Long Integer` | - | - |
| CompletedBy | `String` (255) | - | - |
| Comments | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Machine

**Properties:**

- **Type:** Date

---

#### MachineMaintenanceActionID

**Properties:**

- **Type:** Date

---

#### MaintenanceDate

**Properties:**

- **Type:** Integer

---

#### MaintenanceTime

**Properties:**

- **Type:** Long Integer

---

#### CompletedBy

**Properties:**

- **Type:** String (max length: 255)

---

#### Comments

**Properties:**

- **Type:** String (max length: 255)

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
*Generated at: 2025-11-13T02:36:44Z*
