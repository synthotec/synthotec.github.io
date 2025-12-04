---
layout : default
title : Calibrations
parent : Tables
---
# Calibrations

📊 **Overview:** 4 Fields | 2 Indexes | 1 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 54
- **UUID:** 818F64ABBFC3F74A99C310A3A1521577
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:02Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| EquipmentID | `Long Integer` | 🚫 Not Null | - |
| DateCompleted | `Date` | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `EquipmentID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `CalibrationEquipmentEntity` | [CalibrationEquipment](CalibrationEquipment.md) | `EquipmentID` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `CalibrationResultsSelection` | [CalibrationResults](CalibrationResults.md) | `CalibrationID` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [CalibrationLog](../Forms/CalibrationLog.md) - Data source for CalibrationLog form
- [CalibrationTracker](../Forms/CalibrationTracker.md) - Data source for CalibrationTracker form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:02Z*
