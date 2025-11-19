---
layout : default
title : Advice_Note
parent : Tables
---
# Advice_Note

📊 **Overview:** 6 Fields | 2 Indexes | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 9
- **UUID:** 1C150D42AE7E4341870D4DBFA6AD3288
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:17:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Advice_Note_No | `Date` | ⚡ Auto, 🚫 Not Null | - |
| Customer_Code | `String` (3) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| DespatchDate | `Integer` | - | - |
| ArrivalDate | `Integer` | - | - |
| Transport | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Advice_Note_No` | Keywords | regular | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `CofCSelection` | [CofC](CofC.md) | `Advice_Note_No` → `Advice_Note_No` | Active | - |
| `PickRequestSelection` | [PickRequest](PickRequest.md) | `AdviceNoteID` → `ID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:17:49Z*
