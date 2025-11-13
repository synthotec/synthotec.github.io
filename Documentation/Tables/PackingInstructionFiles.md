---
layout : default
title : PackingInstructionFiles
parent : Tables
---
# PackingInstructionFiles

📊 **Overview:** 8 Fields | 2 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 115
- **UUID:** F461D77AA880C5449A02C9E91E10F836
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:47Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| FileName | `String` (255) | - | - |
| FileBLOB | `Unknown (18)` | - | - |
| UploadedWhen | `String` (255) | - | - |
| UploadedBy | `String` (255) | - | - |
| ProductID | `Date` | - | - |
| Version | `Date` | - | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### FileName

**Properties:**

- **Type:** String (max length: 255)

---

#### FileBLOB

**Properties:**

- **Type:** Unknown (18)

---

#### UploadedWhen

**Properties:**

- **Type:** String (max length: 255)

---

#### UploadedBy

**Properties:**

- **Type:** String (max length: 255)

---

#### ProductID

**Properties:**

- **Type:** Date

---

#### Version

**Properties:**

- **Type:** Date

---

#### MigrationID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ProductID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:47Z*
