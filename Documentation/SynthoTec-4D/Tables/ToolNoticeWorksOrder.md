---
layout : default
title : ToolNoticeWorksOrder
parent : Tables
---
# ToolNoticeWorksOrder

📊 **Overview:** 4 Fields | 4 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 135
- **UUID:** 4B07FFB98BFE74459EB30ECE3B9D6E1F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:20:04Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolNoticeID | `Date` | - | - |
| WorksOrder | `Date` | - | - |
| EmailSent | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolNoticeID` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `EmailSent` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ToolNoticeEntity` | [ToolNotice](ToolNotice.md) | `ToolNoticeID` → `ToolID` | Active | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:20:04Z*
