---
layout : default
title : CalibrationResults
parent : Tables
---
# CalibrationResults

📊 **Overview:** 11 Fields | 2 Indexes | 1 Many-to-One Relations

## 📝 Description

🗨️ Transaction table storing detailed measurement results from calibration tests. Links to Calibrations with pass/fail status and measured values.

## ℹ️ Table Information

- **Table ID:** 91
- **UUID:** 0F3545F5ACE57B499D6C0FBD92F90C78
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:52Z

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
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| CalibrationID | `Long Integer` | 🚫 Not Null | - |
| Type | `Integer` | - | - |
| Description | `String` (255) | 🚫 Not Null | - |
| FileBLOB | `BLOB Scalar` | 🚫 Not Null | - |
| FileName | `String` (255) | 🚫 Not Null | - |
| BooleanResult | `Boolean` | 🚫 Not Null | - |
| NumberResult | `Real` | 🚫 Not Null | - |
| NumberTarget | `Real` | 🚫 Not Null | - |
| TargetMin | `Real` | 🚫 Not Null | - |
| TargetMax | `Real` | 🚫 Not Null | - |

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
*Generated at: 2025-12-04T14:34:52Z*
