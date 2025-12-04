---
layout : default
title : PalletMethods
parent : Tables
---
# PalletMethods

📊 **Overview:** 4 Fields | 1 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 86
- **UUID:** CDB25505B7647A449BCF479500B14E95
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:24:32Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Symbol | `String` (255) | 🚫 Not Null | - |
| BoxesPerPallet | `Integer` | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ProductSelection` | [Product](Product.md) | `PalletMethodID` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [WarehouseOptions](../Forms/WarehouseOptions.md) - Data source for WarehouseOptions form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:32Z*
