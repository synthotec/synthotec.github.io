---
layout : default
title : Grippers
parent : Tables
---
# Grippers

📊 **Overview:** 9 Fields | 5 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 25
- **UUID:** 755FDB8A02ACFB4787F4589BA9B30BE2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:38Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (5)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product_ID | `Long Integer` | 🚫 Not Null | - |
| Part_No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Machine_No | `Integer` | 🚫 Not Null | - |
| Head_No | `String` (10) | 🚫 Not Null | - |
| Gripper_Details | `String` (255) | 🚫 Not Null | - |
| ToolID | `Long Integer` | 🚫 Not Null | - |
| Cleaning_Details | `String` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| MigrationID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Product_ID` | Keywords | regular | - |
| `ToolID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Part_No` | Keywords | regular | - |
| `Machine_No` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `Product_ID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Grippers](../Classes/Grippers.md) - ORDA DataClass class for Grippers table
- [GrippersEntity](../Classes/GrippersEntity.md) - ORDA Entity class for Grippers table

### 📄 Forms

- [ToolManager](../Forms/ToolManager.md) - Data source for ToolManager form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:38Z*
