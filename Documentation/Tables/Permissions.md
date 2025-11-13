---
layout : default
title : Permissions
parent : Tables
---
# Permissions

📊 **Overview:** 2 Fields | 1 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 87
- **UUID:** E8C07233B3BC574991307875E3D2E16F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:06Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (2)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `StaffPermissionsSelection` | [StaffPermissions](StaffPermissions.md) | `PermissionID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:06Z*
