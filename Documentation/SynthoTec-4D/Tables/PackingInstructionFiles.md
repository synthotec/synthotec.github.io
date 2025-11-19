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
- **Generated:** 🕐 2025-11-13T23:19:36Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (1)

---

## 📋 Fields

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

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ProductID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [PackingInstructionFiles](../Classes/PackingInstructionFiles.md) - ORDA DataClass class for PackingInstructionFiles table
- [PackingInstructionFilesEntity](../Classes/PackingInstructionFilesEntity.md) - ORDA Entity class for PackingInstructionFiles table

### 📄 Forms

- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:36Z*
