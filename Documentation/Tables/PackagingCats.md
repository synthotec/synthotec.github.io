---
layout : default
title : PackagingCats
parent : Tables
---
# PackagingCats

📊 **Overview:** 3 Fields | 1 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 36
- **UUID:** 0EB107798546B546BF08F545905BAA5F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:26Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (3)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Name | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### Name

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

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
| `SuppliesSelection` | [Supplies](Supplies.md) | `PackagingCat` → `ID` | Active |

### Detailed Information

#### SuppliesSelection

**Links from:** [Supplies](Supplies.md)

- **Source Table:** `Supplies`
- **Source Field:** `PackagingCat`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:26Z*
