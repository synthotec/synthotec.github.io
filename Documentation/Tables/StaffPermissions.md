---
layout : default
title : StaffPermissions
parent : Tables
---
# StaffPermissions

📊 **Overview:** 5 Fields | 1 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 88
- **UUID:** EBD332232B7BEB469977E8DB6898D40F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:06Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StaffID | `Date` | 🚫 Not Null | - |
| PermissionID | `Date` | 🚫 Not Null | - |
| HasPermission | `Real` | 🚫 Not Null | - |
| LastModified | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `PermissionsEntity` | [Permissions](Permissions.md) | `PermissionID` → `ID` | Active | - |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:06Z*
