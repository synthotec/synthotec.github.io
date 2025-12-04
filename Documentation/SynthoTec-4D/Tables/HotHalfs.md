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
- **Generated:** 🕐 2025-12-03T16:23:54Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | 🚫 Not Null | - |
| Count | `Long Integer` | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

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

- [HotHalfs](../Classes/HotHalfs.md) - ORDA DataClass class for HotHalfs table
- [HotHalfsEntity](../Classes/HotHalfsEntity.md) - ORDA Entity class for HotHalfs table

### 📄 Forms

- [HotHalfManager](../Forms/HotHalfManager.md) - Data source for HotHalfManager form
- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:54Z*
