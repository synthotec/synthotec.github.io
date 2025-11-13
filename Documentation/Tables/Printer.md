---
layout : default
title : Printer
parent : Tables
---
# Printer

📊 **Overview:** 9 Fields | 4 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 118
- **UUID:** C5724BFA139A9141B0B974FDE6810417
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:42Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| Type | `Date` | - | - |
| Port | `String` (255) | - | - |
| Model | `String` (255) | - | - |
| Computer | `String` (255) | - | - |
| Options | `Object` | - | - |
| Active | `Real` | - | - |
| UpdateOptions | `Real` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Computer` | Keywords | regular | - |
| `Active` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `UpdateOptions` | Keywords | regular | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `PrinterID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Printer](../Classes/Printer.md) - DataClass class
- [PrinterEntity](../Classes/PrinterEntity.md) - Entity class
- [PrinterSelection](../Classes/PrinterSelection.md) - EntitySelection class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:42Z*
