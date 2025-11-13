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
- **Generated:** 🕐 2025-11-13T02:36:52Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Name

**Properties:**

- **Type:** String (max length: 255)

---

#### MigrationID

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
| `ToolTemperatureTargetSelection` | [ToolTemperatureTarget](ToolTemperatureTarget.md) | `ZoneID` → `ID` | Active |

### Detailed Information

#### ToolTemperatureTargetSelection

**Links from:** [ToolTemperatureTarget](ToolTemperatureTarget.md)

- **Source Table:** `ToolTemperatureTarget`
- **Source Field:** `ZoneID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:52Z*
