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
- **Generated:** 🕐 2025-11-13T02:36:50Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Name | `String` (255) | - | - |
| Type | `Date` | - | - |
| Port | `String` (255) | - | - |
| Model | `String` (255) | - | - |
| Computer | `String` (255) | - | - |
| Options | `Unknown (21)` | - | - |
| Active | `Real` | - | - |
| UpdateOptions | `Real` | - | - |

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

#### Type

**Properties:**

- **Type:** Date

---

#### Port

**Properties:**

- **Type:** String (max length: 255)

---

#### Model

**Properties:**

- **Type:** String (max length: 255)

---

#### Computer

**Properties:**

- **Type:** String (max length: 255)

---

#### Options

**Properties:**

- **Type:** Unknown (21)

---

#### Active

**Properties:**

- **Type:** Real

---

#### UpdateOptions

**Properties:**

- **Type:** Real

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Computer` | Keywords | regular | - |
| `Active` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `UpdateOptions` | Keywords | regular | - |

### Detailed Information

- **Field:** `Computer`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Active`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `UpdateOptions`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `PrintJobSelection` | [PrintJob](PrintJob.md) | `PrinterID` → `ID` | Active |

### Detailed Information

#### PrintJobSelection

**Links from:** [PrintJob](PrintJob.md)

- **Source Table:** `PrintJob`
- **Source Field:** `PrinterID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:50Z*
