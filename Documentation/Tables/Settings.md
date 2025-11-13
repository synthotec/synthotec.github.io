---
layout : default
title : Settings
parent : Tables
---
# Settings

📊 **Overview:** 4 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 82
- **UUID:** 693874A53327EC4980F6359376A41BBD
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:00Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| VariableName | `String` (255) | 🚫 Not Null | - |
| Object | `Object` | 🚫 Not Null | - |
| StaffID | `Date` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `StaffID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `VariableName` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Settings](../Classes/Settings.md) - DataClass class
- [SettingsEntity](../Classes/SettingsEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:00Z*
