---
layout : default
title : PrintJob
parent : Tables
---
# PrintJob

📊 **Overview:** 11 Fields | 5 Indexes | 3 Many-to-One Relations

## 📝 Description

🗨️ Transaction table queueing and tracking print jobs. Records label print requests, status, and completion for production and shipping labels.

## ℹ️ Table Information

- **Table ID:** 126
- **UUID:** B29FF560CBF45F4FB415A4450511F8C1
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:25Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (5)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PrinterID | `Long Integer` | - | - |
| Printed | `Boolean` | 🚫 Not Null | - |
| FormName | `String` (255) | - | - |
| FormData | `Object` | - | - |
| Orientation | `Integer` | - | - |
| PaperName | `String` (255) | - | - |
| Copies | `Integer` | - | - |
| RelatedUUID | `String` | - | - |
| TimeStamp | `String` (255) | - | - |
| StaffID | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `RelatedUUID` | Keywords | regular | - |
| `StaffID` | Keywords | regular | - |
| `Printed` | Keywords | regular | - |
| `PrinterID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `PrinterEntity` | [Printer](Printer.md) | `PrinterID` → `ID` | Active | - |
| `PalletEntity` | [Pallet](Pallet.md) | `RelatedUUID` → `UUID` | Active | - |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [PrintJobEntity](../Classes/PrintJobEntity.md) - ORDA Entity class for PrintJob table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:25Z*
