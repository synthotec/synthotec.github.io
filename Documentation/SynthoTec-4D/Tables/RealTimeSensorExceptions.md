---
layout : default
title : RealTimeSensorExceptions
parent : Tables
---
# RealTimeSensorExceptions

📊 **Overview:** 8 Fields | 3 Indexes | 4 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 117
- **UUID:** 0ED7579A95D51547A48FD7693363C503
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:39Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| FirstRealTimeID | `Date` | - | - |
| LastRealTimeID | `Date` | - | - |
| WorksOrder | `Date` | - | - |
| Acknowledged | `Real` | 🚫 Not Null | - |
| StaffID | `Date` | - | - |
| Comment | `String` (255) | - | - |
| RouteCards | `String` (255) | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `WorksOrder` | Keywords | regular | - |
| `Acknowledged` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `FirstRealTimeEntity` | [RealTime](RealTime.md) | `FirstRealTimeID` → `ID` | Active | - |
| `LastRealTimeEntity` | [RealTime](RealTime.md) | `LastRealTimeID` → `ID` | Active | - |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active | - |

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:39Z*
