---
layout : default
title : ErrorDetail
parent : Tables
---
# ErrorDetail

📊 **Overview:** 7 Fields | 4 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 132
- **UUID:** E06316D0DEB08A45A8A203D136C74702
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:58Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ErrorID | `String` | - | - |
| Date | `Integer` | - | - |
| Time | `Long Integer` | - | - |
| ErrorObject | `Object` | - | - |
| User | `String` (255) | - | - |
| Machine | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Date` | Keywords | regular | - |
| `ErrorID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Time` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ErrorEntity` | [Error](Error.md) | `ErrorID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:58Z*
