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
- **Generated:** 🕐 2025-11-13T02:35:52Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| EquipmentID | `Date` | 🚫 Not Null | - |
| DateCompleted | `Integer` | 🚫 Not Null | - |
| CompletedBy | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### EquipmentID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DateCompleted

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CompletedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `EquipmentID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `EquipmentID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CalibrationEquipmentEntity` | [CalibrationEquipment](CalibrationEquipment.md) | `EquipmentID` → `ID` | Active |

### Detailed Information

#### CalibrationEquipmentEntity

**Links to:** [CalibrationEquipment](CalibrationEquipment.md)

- **Source Field:** `EquipmentID`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `CalibrationResultsSelection` | [CalibrationResults](CalibrationResults.md) | `CalibrationID` → `ID` | Active |

### Detailed Information

#### CalibrationResultsSelection

**Links from:** [CalibrationResults](CalibrationResults.md)

- **Source Table:** `CalibrationResults`
- **Source Field:** `CalibrationID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:52Z*
