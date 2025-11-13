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
- **Generated:** 🕐 2025-11-13T02:35:27Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **UniqueID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Tool_ID | `Date` | 🚫 Not Null | - |
| Date | `Integer` | 🚫 Not Null | - |
| Description | `String` | 🚫 Not Null | - |
| PO_ID | `Date` | 🚫 Not Null | - |
| Reason | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 UniqueID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### Tool_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Description

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### PO_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Reason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `UniqueID` | B-Tree | regular | ✨ Yes |

### Detailed Information

- **Field:** `UniqueID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** B-Tree

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `Tool_ID` → `Tool_ID` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `Tool_ID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:27Z*
