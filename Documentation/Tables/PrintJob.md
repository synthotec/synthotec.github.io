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
- **Generated:** 🕐 2025-11-13T02:36:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (5)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PrinterID | `Date` | - | - |
| Printed | `Real` | 🚫 Not Null | - |
| FormName | `String` (255) | - | - |
| FormData | `Unknown (21)` | - | - |
| Orientation | `Picture` | - | - |
| PaperName | `String` (255) | - | - |
| Copies | `Picture` | - | - |
| RelatedUUID | `String` | - | - |
| TimeStamp | `String` (255) | - | - |
| StaffID | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### PrinterID

**Properties:**

- **Type:** Date

---

#### Printed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### FormName

**Properties:**

- **Type:** String (max length: 255)

---

#### FormData

**Properties:**

- **Type:** Unknown (21)

---

#### Orientation

**Properties:**

- **Type:** Picture

---

#### PaperName

**Properties:**

- **Type:** String (max length: 255)

---

#### Copies

**Properties:**

- **Type:** Picture

---

#### RelatedUUID

**Properties:**

- **Type:** String

---

#### TimeStamp

**Properties:**

- **Type:** String (max length: 255)

---

#### StaffID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `RelatedUUID` | Keywords | regular | - |
| `StaffID` | Keywords | regular | - |
| `Printed` | Keywords | regular | - |
| `PrinterID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RelatedUUID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `StaffID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Printed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PrinterID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `PrinterEntity` | [Printer](Printer.md) | `PrinterID` → `ID` | Active |
| `PalletEntity` | [Pallet](Pallet.md) | `RelatedUUID` → `UUID` | Active |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active |

### Detailed Information

#### PrinterEntity

**Links to:** [Printer](Printer.md)

- **Source Field:** `PrinterID`
- **Destination Field:** `ID`
- **State:** Active

---

#### PalletEntity

**Links to:** [Pallet](Pallet.md)

- **Source Field:** `RelatedUUID`
- **Destination Field:** `UUID`
- **State:** Active

---

#### StaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:57Z*
