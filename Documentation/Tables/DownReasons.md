---
layout : default
title : DownReasons
parent : Tables
---
# DownReasons

📊 **Overview:** 5 Fields | 3 Indexes | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 64
- **UUID:** 223300B659C4B94286C058AC2F0A57CC
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:01Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Category | `String` (255) | 🚫 Not Null | - |
| Reason | `String` (255) | 🚫 Not Null | - |
| Exclude | `Real` | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Category

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Reason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Exclude

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Archive

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Archive` | Keywords | regular | - |
| `Exclude` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Archive`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Exclude`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `RealTimeSelection` | [RealTime](RealTime.md) | `DownReason` → `ID` | Active |
| `RealTimeMachinesSelection` | [RealTimeMachines](RealTimeMachines.md) | `DownReason` → `ID` | Active |

### Detailed Information

#### RealTimeSelection

**Links from:** [RealTime](RealTime.md)

- **Source Table:** `RealTime`
- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** Active

---

#### RealTimeMachinesSelection

**Links from:** [RealTimeMachines](RealTimeMachines.md)

- **Source Table:** `RealTimeMachines`
- **Source Field:** `DownReason`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:01Z*
