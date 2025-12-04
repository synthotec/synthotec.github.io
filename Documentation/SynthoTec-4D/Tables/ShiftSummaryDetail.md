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
- **Generated:** 🕐 2025-12-03T16:25:12Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Long Integer` | - | - |
| RealTimeOutputMachine | `Object` | - | - |
| Commentary | `String` | - | - |
| ShiftSummaryID | `Long Integer` | - | - |
| DowntimeSincePrevious | `Time` | - | - |

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

## 🔗 Related Items

### 📦 Classes

- [ShiftSummaryDetailEntity](../Classes/ShiftSummaryDetailEntity.md) - ORDA Entity class for ShiftSummaryDetail table

### 📄 Forms

- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:25:12Z*
