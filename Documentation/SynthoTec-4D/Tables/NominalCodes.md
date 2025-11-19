---
layout : default
title : NominalCodes
parent : Tables
---
# NominalCodes

📊 **Overview:** 6 Fields | 3 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 84
- **UUID:** B4B021F72621A44A861BDFF8762EE00C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:02Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| NominalCode | `Date` | ✨ Unique | - |
| Description | `String` (255) | 🚫 Not Null | - |
| Code_4D | `String` (255) | 🚫 Not Null | - |
| Category | `String` (255) | 🚫 Not Null | - |
| FinishedGoodsTransport | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `FinishedGoodsTransport` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `NominalCode` | B-Tree | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `NominalCode` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:02Z*
