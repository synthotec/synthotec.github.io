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
- **Generated:** 🕐 2025-11-13T02:35:24Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### EquipmentName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### UsageFrequency

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Wear

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Environment

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Sensitivity

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### InternallyCalibrated

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### EquipmentLocation

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Contact

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Notes

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Visible_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Archived

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Serial

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Archived` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Archived`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `CalibrationsSelection` | [Calibrations](Calibrations.md) | `EquipmentID` → `ID` | Active |
| `CalibrationProceduresSelection` | [CalibrationProcedures](CalibrationProcedures.md) | `EquipmentID` → `ID` | Active |

### Detailed Information

#### CalibrationsSelection

**Links from:** [Calibrations](Calibrations.md)

- **Source Table:** `Calibrations`
- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** Active

---

#### CalibrationProceduresSelection

**Links from:** [CalibrationProcedures](CalibrationProcedures.md)

- **Source Table:** `CalibrationProcedures`
- **Source Field:** `EquipmentID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:24Z*
