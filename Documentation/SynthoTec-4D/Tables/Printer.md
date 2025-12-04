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
- **Generated:** 🕐 2025-12-03T16:25:01Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (3)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| Type | `Long Integer` | - | - |
| Port | `String` (255) | - | - |
| Model | `String` (255) | - | - |
| Computer | `String` (255) | - | - |
| Options | `Object` | - | - |
| Active | `Boolean` | - | - |
| UpdateOptions | `Boolean` | - | - |

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

- [Printer](../Classes/Printer.md) - ORDA DataClass class for Printer table
- [PrinterEntity](../Classes/PrinterEntity.md) - ORDA Entity class for Printer table
- [PrinterSelection](../Classes/PrinterSelection.md) - ORDA EntitySelection class for Printer table

### 📄 Forms

- [PrinterManagement](../Forms/PrinterManagement.md) - Data source for PrinterManagement form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:25:01Z*
