---
layout : default
title : CalibrationEquipment
parent : Tables
---
# CalibrationEquipment

📊 **Overview:** 13 Fields | 2 Indexes | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 34
- **UUID:** 8043B353374B8C40B4E421933BA42318
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:46Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| EquipmentName | `String` (255) | 🚫 Not Null | - |
| UsageFrequency | `Integer` | 🚫 Not Null | - |
| Wear | `Integer` | 🚫 Not Null | - |
| Environment | `Integer` | 🚫 Not Null | - |
| Sensitivity | `Integer` | 🚫 Not Null | - |
| InternallyCalibrated | `Boolean` | 🚫 Not Null | - |
| EquipmentLocation | `String` (255) | 🚫 Not Null | - |
| Contact | `String` (255) | 🚫 Not Null | - |
| Notes | `String` (255) | 🚫 Not Null | - |
| Visible_ID | `Long Integer` | 🚫 Not Null | - |
| Archived | `Boolean` | 🚫 Not Null | - |
| Serial | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Archived` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `CalibrationsSelection` | [Calibrations](Calibrations.md) | `EquipmentID` → `ID` | Active | - |
| `CalibrationProceduresSelection` | [CalibrationProcedures](CalibrationProcedures.md) | `EquipmentID` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [CalibrationLog](../Forms/CalibrationLog.md) - Data source for CalibrationLog form
- [CalibrationProcedures](../Forms/CalibrationProcedures.md) - Data source for CalibrationProcedures form
- [CalibrationTracker](../Forms/CalibrationTracker.md) - Data source for CalibrationTracker form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:46Z*
