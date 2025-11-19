---
layout : default
title : PrintJob
parent : Tables
---
# PrintJob

📊 **Overview:** 11 Fields | 5 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 126
- **UUID:** B29FF560CBF45F4FB415A4450511F8C1
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:52Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (5)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PrinterID | `Date` | - | - |
| Printed | `Real` | 🚫 Not Null | - |
| FormName | `String` (255) | - | - |
| FormData | `Object` | - | - |
| Orientation | `Picture` | - | - |
| PaperName | `String` (255) | - | - |
| Copies | `Picture` | - | - |
| RelatedUUID | `String` | - | - |
| TimeStamp | `String` (255) | - | - |
| StaffID | `Date` | - | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:52Z*
