---
layout : default
title : RTSUM
parent : Tables
---
# RTSUM

📊 **Overview:** 10 Fields | 4 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 67
- **UUID:** B4BCF8D18A05AB4AB5784486D50CD234
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:18:44Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (10)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| dDate | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| Stoppage | `Real` | 🚫 Not Null | - |
| DownCode | `Date` | 🚫 Not Null | - |
| Impressions | `Date` | 🚫 Not Null | - |
| Seconds | `Boolean` | 🚫 Not Null | - |
| Instances | `Picture` | 🚫 Not Null | - |
| Target | `Boolean` | 🚫 Not Null | - |
| TC | `Real` | 🚫 Not Null | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:44Z*
