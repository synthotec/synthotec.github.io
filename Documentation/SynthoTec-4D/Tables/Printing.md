---
layout : default
title : Printing
parent : Tables
---
# Printing

📊 **Overview:** 7 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 15
- **UUID:** 46AB44AA8924F449BCCF65AD27E8BDC1
- **Primary Key:** 🔑 `Unique_ID`
- **Generated:** 🕐 2025-11-13T23:17:54Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Unique_ID** | `Date` | 🔑 PK, ✨ Unique, ⚠️ Required, 🚫 Not Null | - |
| User_Name | `String` (40) | 🚫 Not Null | - |
| Report | `String` (40) | 🚫 Not Null | - |
| Parameter1 | `String` (20) | 🚫 Not Null | - |
| Parameter2 | `String` (20) | 🚫 Not Null | - |
| labelpartno | `String` (30) | 🚫 Not Null | - |
| PrintDate_d | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Unique_ID` | Keywords | regular | ✨ Yes |

## 🔗 Related Items

### 📦 Classes

- [PrintingEntity](../Classes/PrintingEntity.md) - ORDA Entity class for Printing table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:54Z*
