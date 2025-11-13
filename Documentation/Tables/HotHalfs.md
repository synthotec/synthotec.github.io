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
- **Generated:** 🕐 2025-11-13T02:35:32Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | 🚫 Not Null | - |
| Count | `Date` | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

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

#### Count

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Description

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Name` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Name`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ToolsSelection` | [Tools](Tools.md) | `HotHalfID` → `ID` | Active |

### Detailed Information

#### ToolsSelection

**Links from:** [Tools](Tools.md)

- **Source Table:** `Tools`
- **Source Field:** `HotHalfID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:32Z*
