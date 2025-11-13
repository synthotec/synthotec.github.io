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
- **Generated:** 🕐 2025-11-13T02:36:23Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| StaffID | `Date` | 🚫 Not Null | - |
| PermissionID | `Date` | 🚫 Not Null | - |
| HasPermission | `Real` | 🚫 Not Null | - |
| LastModified | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### StaffID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PermissionID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### HasPermission

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### LastModified

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

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `PermissionsEntity` | [Permissions](Permissions.md) | `PermissionID` → `ID` | Active |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active |

### Detailed Information

#### PermissionsEntity

**Links to:** [Permissions](Permissions.md)

- **Source Field:** `PermissionID`
- **Destination Field:** `ID`
- **State:** Active

---

#### StaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:23Z*
