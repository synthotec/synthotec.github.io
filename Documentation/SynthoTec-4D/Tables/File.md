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
- **Generated:** 🕐 2025-12-03T16:25:14Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| Blob | `BLOB Scalar` | - | - |
| UploadTimestamp | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `CustomerSelection` | [Customer](Customer.md) | `TransportInstructionFileID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [File](../Classes/File.md) - ORDA DataClass class for File table
- [FileEntity](../Classes/FileEntity.md) - ORDA Entity class for File table

### 📄 Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:25:14Z*
