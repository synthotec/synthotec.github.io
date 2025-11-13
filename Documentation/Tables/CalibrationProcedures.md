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
- **Generated:** 🕐 2025-11-13T02:49:10Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| EquipmentID | `Date` | 🚫 Not Null | - |
| ProcedureName | `String` (255) | 🚫 Not Null | - |
| ProcedureType | `Picture` | 🚫 Not Null | - |
| TargetResult | `Boolean` | 🚫 Not Null | - |
| MinResult | `Boolean` | 🚫 Not Null | - |
| MaxResult | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `EquipmentID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `CalibrationEquipmentENtity` | [CalibrationEquipment](CalibrationEquipment.md) | `EquipmentID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:10Z*
