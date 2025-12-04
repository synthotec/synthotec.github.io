---
layout : default
title : RTSUM
parent : Tables
---
# RTSUM

📊 **Overview:** 10 Fields | 4 Indexes | 1 Many-to-One Relations

## 📝 Description

🗨️ Summary table aggregating real-time production data by period. Provides pre-calculated totals for reporting and dashboard displays.

## ℹ️ Table Information

- **Table ID:** 67
- **UUID:** B4BCF8D18A05AB4AB5784486D50CD234
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:29Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (10)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (3)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| dDate | `Date` | 🚫 Not Null | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| Stoppage | `Boolean` | 🚫 Not Null | - |
| DownCode | `Long Integer` | 🚫 Not Null | - |
| Impressions | `Long Integer` | 🚫 Not Null | - |
| Seconds | `Real` | 🚫 Not Null | - |
| Instances | `Integer` | 🚫 Not Null | - |
| Target | `Real` | 🚫 Not Null | - |
| TC | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `dDate` | Cluster | regular | - |
| `Stoppage` | Cluster | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `WorksOrder` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [RTSUM](../Classes/RTSUM.md) - ORDA DataClass class for RTSUM table
- [RTSUMSelection](../Classes/RTSUMSelection.md) - ORDA EntitySelection class for RTSUM table

### 📄 Forms

- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:29Z*
