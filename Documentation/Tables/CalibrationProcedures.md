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
- **Generated:** 🕐 2025-11-13T02:36:25Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| EquipmentID | `Date` | 🚫 Not Null | - |
| ProcedureName | `String` (255) | 🚫 Not Null | - |
| ProcedureType | `Picture` | 🚫 Not Null | - |
| TargetResult | `Boolean` | 🚫 Not Null | - |
| MinResult | `Boolean` | 🚫 Not Null | - |
| MaxResult | `Boolean` | 🚫 Not Null | - |

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

#### ProcedureName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ProcedureType

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### TargetResult

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### MinResult

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### MaxResult

**Properties:**

- **Type:** Boolean
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
| `CalibrationEquipmentENtity` | [CalibrationEquipment](CalibrationEquipment.md) | `EquipmentID` → `ID` | Active |

### Detailed Information

#### CalibrationEquipmentENtity

**Links to:** [CalibrationEquipment](CalibrationEquipment.md)

- **Source Field:** `EquipmentID`
- **Destination Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:25Z*
