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
- **Generated:** 🕐 2025-11-13T23:19:04Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Symbol | `String` (255) | 🚫 Not Null | - |
| BoxesPerPallet | `Picture` | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ProductSelection` | [Product](Product.md) | `PalletMethodID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:04Z*
