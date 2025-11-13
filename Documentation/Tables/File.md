---
layout : default
title : File
parent : Tables
---
# File

📊 **Overview:** 4 Fields | 1 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 133
- **UUID:** 42DDF5081B29E94091C7359EF587793D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:24Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| Blob | `Unknown (18)` | - | - |
| UploadTimestamp | `String` (255) | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Name

**Properties:**

- **Type:** String (max length: 255)

---

#### Blob

**Properties:**

- **Type:** Unknown (18)

---

#### UploadTimestamp

**Properties:**

- **Type:** String (max length: 255)

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
| `CustomerSelection` | [Customer](Customer.md) | `TransportInstructionFileID` → `ID` | Active |

### Detailed Information

#### CustomerSelection

**Links from:** [Customer](Customer.md)

- **Source Table:** `Customer`
- **Source Field:** `TransportInstructionFileID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:37:24Z*
