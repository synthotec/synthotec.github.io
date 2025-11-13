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
- **Generated:** 🕐 2025-11-13T02:36:26Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### CalibrationID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Type

**Properties:**

- **Type:** Picture

---

#### Description

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FileBLOB

**Properties:**

- **Type:** Unknown (18)
- **Constraints:** 🚫 Never Null

---

#### FileName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### BooleanResult

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NumberResult

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### NumberTarget

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TargetMin

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TargetMax

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `CalibrationID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `CalibrationID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CalibrationsEntity` | [Calibrations](Calibrations.md) | `CalibrationID` → `ID` | Active |

### Detailed Information

#### CalibrationsEntity

**Links to:** [Calibrations](Calibrations.md)

- **Source Field:** `CalibrationID`
- **Destination Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:26Z*
