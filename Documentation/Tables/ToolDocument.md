---
layout : default
title : ToolDocument
parent : Tables
---
# ToolDocument

📊 **Overview:** 5 Fields | 2 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 122
- **UUID:** 7D2816DD1753484DA778A019D7B75188
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:53Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolID | `Date` | - | - |
| FileName | `String` (255) | - | - |
| FileBLOB | `Unknown (18)` | - | - |
| Name | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ToolID

**Properties:**

- **Type:** Date

---

#### FileName

**Properties:**

- **Type:** String (max length: 255)

---

#### FileBLOB

**Properties:**

- **Type:** Unknown (18)

---

#### Name

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `ToolID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolsEntity` | [Tools](Tools.md) | `ToolID` → `Tool_ID` | Active |

### Detailed Information

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `ToolID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:53Z*
