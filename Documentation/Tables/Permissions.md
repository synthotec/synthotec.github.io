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
- **Generated:** 🕐 2025-11-13T02:36:22Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (2)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Name

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `StaffPermissionsSelection` | [StaffPermissions](StaffPermissions.md) | `PermissionID` → `ID` | Active |

### Detailed Information

#### StaffPermissionsSelection

**Links from:** [StaffPermissions](StaffPermissions.md)

- **Source Table:** `StaffPermissions`
- **Source Field:** `PermissionID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:22Z*
