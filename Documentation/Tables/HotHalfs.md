---
layout : default
title : HotHalfs
parent : Tables
---
# HotHalfs

📊 **Overview:** 5 Fields | 2 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 45
- **UUID:** B129C8DCAC2B444CB303898B002AAF6E
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:48:16Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | 🚫 Not Null | - |
| Count | `Date` | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Name` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `ToolsSelection` | [Tools](Tools.md) | `HotHalfID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [HotHalfs](../Classes/HotHalfs.md) - DataClass class
- [HotHalfsEntity](../Classes/HotHalfsEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:16Z*
