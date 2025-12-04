---
layout : default
title : Settings
parent : Tables
---
# Settings

📊 **Overview:** 4 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 82
- **UUID:** 693874A53327EC4980F6359376A41BBD
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:28Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (9)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| VariableName | `String` (255) | 🚫 Not Null | - |
| Object | `Object` | 🚫 Not Null | - |
| StaffID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `StaffID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `VariableName` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Settings](../Classes/Settings.md) - ORDA DataClass class for Settings table
- [SettingsEntity](../Classes/SettingsEntity.md) - ORDA Entity class for Settings table

### 📄 Forms

- [%2AMethodList](../Forms/%2AMethodList.md) - Data source for %2AMethodList form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [LabelHistory](../Forms/LabelHistory.md) - Data source for LabelHistory form
- [LocationManager](../Forms/LocationManager.md) - Data source for LocationManager form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [ProcurementProgramImporter](../Forms/ProcurementProgramImporter.md) - Data source for ProcurementProgramImporter form
- [Schedule_Variables](../Forms/Schedule_Variables.md) - Data source for Schedule_Variables form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:28Z*
