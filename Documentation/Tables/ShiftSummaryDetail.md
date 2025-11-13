---
layout : default
title : ShiftSummaryDetail
parent : Tables
---
# ShiftSummaryDetail

📊 **Overview:** 6 Fields | 2 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 130
- **UUID:** 72508DC4C8B6954DB9CFBCAC2709E212
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:49:56Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Date` | - | - |
| RealTimeOutputMachine | `Object` | - | - |
| Commentary | `String` | - | - |
| ShiftSummaryID | `Date` | - | - |
| DowntimeSincePrevious | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `WorksOrder` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ShiftSummaryEntity` | [ShiftSummary](ShiftSummary.md) | `ShiftSummaryID` → `ID` | Active | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:49:56Z*
