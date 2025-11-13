---
layout : default
title : QualitySystemProcedures
parent : Tables
---
# QualitySystemProcedures

📊 **Overview:** 9 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 100
- **UUID:** BBEBD957B57394498D952926A484488F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:34Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Date` | 🚫 Not Null | - |
| System | `String` (255) | 🚫 Not Null | - |
| Procedure | `String` (255) | 🚫 Not Null | - |
| TargetMin | `Boolean` | 🚫 Not Null | - |
| TargetMax | `Boolean` | 🚫 Not Null | - |
| ForEachCavity | `Real` | 🚫 Not Null | - |
| ProcedureOrder | `Picture` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### System

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Procedure

**Properties:**

- **Type:** String (max length: 255)
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

#### ForEachCavity

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ProcedureOrder

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ProductID` | Keywords | regular | - |
| `System` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `System`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:34Z*
