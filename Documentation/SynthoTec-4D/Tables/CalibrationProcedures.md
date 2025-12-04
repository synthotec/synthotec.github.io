---
layout : default
title : CalibrationProcedures
parent : Tables
---
# CalibrationProcedures

📊 **Overview:** 7 Fields | 2 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 90
- **UUID:** 1A64E1E52A2717409460B15ADE9D3AA3
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:36Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| EquipmentID | `Long Integer` | 🚫 Not Null | - |
| ProcedureName | `String` (255) | 🚫 Not Null | - |
| ProcedureType | `Integer` | 🚫 Not Null | - |
| TargetResult | `Real` | 🚫 Not Null | - |
| MinResult | `Real` | 🚫 Not Null | - |
| MaxResult | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `EquipmentID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `CalibrationEquipmentENtity` | [CalibrationEquipment](CalibrationEquipment.md) | `EquipmentID` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [CalibrationLog](../Forms/CalibrationLog.md) - Data source for CalibrationLog form
- [CalibrationProcedures](../Forms/CalibrationProcedures.md) - Data source for CalibrationProcedures form
- [CalibrationTracker](../Forms/CalibrationTracker.md) - Data source for CalibrationTracker form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:36Z*
