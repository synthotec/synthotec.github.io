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
- **Generated:** 🕐 2025-11-13T02:36:51Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ToolID

**Properties:**

- **Type:** Date

---

#### ZoneID

**Properties:**

- **Type:** Date

---

#### Target

**Properties:**

- **Type:** Boolean

---

#### Min

**Properties:**

- **Type:** Boolean

---

#### Max

**Properties:**

- **Type:** Boolean

---

#### StaffID

**Properties:**

- **Type:** Date

---

#### LastUpdated

**Properties:**

- **Type:** String (max length: 255)

---

#### MigrationID

**Properties:**

- **Type:** Undefined

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolID` | Keywords | regular | - |
| `ZoneID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ZoneID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |
| `ToolTemperatureZoneEntity` | [ToolTemperatureZone](ToolTemperatureZone.md) | `ZoneID` → `ID` | Active |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

#### ToolTemperatureZoneEntity

**Links to:** [ToolTemperatureZone](ToolTemperatureZone.md)

- **Source Field:** `ZoneID`
- **Destination Field:** `ID`
- **State:** Active

---

#### StaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:51Z*
