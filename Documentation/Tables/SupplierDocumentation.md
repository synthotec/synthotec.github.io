---
layout : default
title : SupplierDocumentation
parent : Tables
---
# SupplierDocumentation

📊 **Overview:** 9 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 85
- **UUID:** 39E8E2BA6606BA4E97B23381CEBA900D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T16:09:05Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| SupplierID | `Date` | 🚫 Not Null | - |
| DocumentType | `String` (255) | 🚫 Not Null | - |
| DocumentReference | `String` (255) | 🚫 Not Null | - |
| File | `Unknown (18)` | 🚫 Not Null | - |
| DateAdded | `Integer` | 🚫 Not Null | - |
| DateValidUntil | `Integer` | 🚫 Not Null | - |
| FileName | `String` (255) | 🚫 Not Null | - |
| Archived | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `DateValidUntil` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Archived` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `SuppliersEntity` | [Suppliers](Suppliers.md) | `SupplierID` → `SupplierID_l` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:09:05Z*
