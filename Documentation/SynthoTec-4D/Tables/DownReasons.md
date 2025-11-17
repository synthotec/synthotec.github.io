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
- **Generated:** 🕐 2025-11-13T23:18:41Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (5)
- [🔍 Indexes](#-indexes) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Category | `String` (255) | 🚫 Not Null | - |
| Reason | `String` (255) | 🚫 Not Null | - |
| Exclude | `Real` | 🚫 Not Null | - |
| Archive | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Archive` | Keywords | regular | - |
| `Exclude` | Keywords | regular | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `RealTimeSelection` | [RealTime](RealTime.md) | `DownReason` → `ID` | Active | - |
| `RealTimeMachinesSelection` | [RealTimeMachines](RealTimeMachines.md) | `DownReason` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:41Z*
