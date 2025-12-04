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
- **Generated:** 🕐 2025-12-03T16:24:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductID | `Long Integer` | 🚫 Not Null | - |
| System | `String` (255) | 🚫 Not Null | - |
| Procedure | `String` (255) | 🚫 Not Null | - |
| TargetMin | `Real` | 🚫 Not Null | - |
| TargetMax | `Real` | 🚫 Not Null | - |
| ForEachCavity | `Boolean` | 🚫 Not Null | - |
| ProcedureOrder | `Integer` | 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ProductID` | Keywords | regular | - |
| `System` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [QualitySystemProcedures](../Classes/QualitySystemProcedures.md) - ORDA DataClass class for QualitySystemProcedures table
- [QualitySystemProceduresEntity](../Classes/QualitySystemProceduresEntity.md) - ORDA Entity class for QualitySystemProcedures table

### 📄 Forms

- [QualitySystemProcedures](../Forms/QualitySystemProcedures.md) - Data source for QualitySystemProcedures form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:45Z*
