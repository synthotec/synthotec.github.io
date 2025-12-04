---
layout : default
title : ToolLog
parent : Tables
---
# ToolLog

📊 **Overview:** 6 Fields | 1 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 37
- **UUID:** FD6A501D6913B94C884BCFC8E8930241
- **Primary Key:** 🔑 `UniqueID`
- **Generated:** 🕐 2025-12-03T16:23:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **UniqueID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Tool_ID | `Long Integer` | 🚫 Not Null | - |
| Date | `Date` | 🚫 Not Null | - |
| Description | `String` | 🚫 Not Null | - |
| PO_ID | `Long Integer` | 🚫 Not Null | - |
| Reason | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `UniqueID` | B-Tree | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolsEntity` | [Tools](Tools.md) | `Tool_ID` → `Tool_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [ToolLogEntity](../Classes/ToolLogEntity.md) - ORDA Entity class for ToolLog table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:49Z*
