---
layout : default
title : CalibrationResults
parent : Tables
---
# CalibrationResults

📊 **Overview:** 11 Fields | 2 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 91
- **UUID:** 0F3545F5ACE57B499D6C0FBD92F90C78
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:09Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| CalibrationID | `Date` | 🚫 Not Null | - |
| Type | `Picture` | - | - |
| Description | `String` (255) | 🚫 Not Null | - |
| FileBLOB | `Unknown (18)` | 🚫 Not Null | - |
| FileName | `String` (255) | 🚫 Not Null | - |
| BooleanResult | `Real` | 🚫 Not Null | - |
| NumberResult | `Boolean` | 🚫 Not Null | - |
| NumberTarget | `Boolean` | 🚫 Not Null | - |
| TargetMin | `Boolean` | 🚫 Not Null | - |
| TargetMax | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `CalibrationID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `CalibrationsEntity` | [Calibrations](Calibrations.md) | `CalibrationID` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [CalibrationLog](../Forms/CalibrationLog.md) - Data source for CalibrationLog form
- [CalibrationTracker](../Forms/CalibrationTracker.md) - Data source for CalibrationTracker form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:09Z*
