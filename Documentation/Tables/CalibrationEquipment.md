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
- **Generated:** 🕐 2025-11-13T16:08:21Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| EquipmentName | `String` (255) | 🚫 Not Null | - |
| UsageFrequency | `Picture` | 🚫 Not Null | - |
| Wear | `Picture` | 🚫 Not Null | - |
| Environment | `Picture` | 🚫 Not Null | - |
| Sensitivity | `Picture` | 🚫 Not Null | - |
| InternallyCalibrated | `Real` | 🚫 Not Null | - |
| EquipmentLocation | `String` (255) | 🚫 Not Null | - |
| Contact | `String` (255) | 🚫 Not Null | - |
| Notes | `String` (255) | 🚫 Not Null | - |
| Visible_ID | `Date` | 🚫 Not Null | - |
| Archived | `Real` | 🚫 Not Null | - |
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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:21Z*
