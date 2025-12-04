---
layout : default
title : RealTimeSensorExceptions
parent : Tables
---
# RealTimeSensorExceptions

📊 **Overview:** 8 Fields | 3 Indexes | 4 Many-to-One Relations

## 📝 Description

🗨️ Alert table recording sensor anomalies and out-of-range readings. Flags equipment issues requiring attention based on predefined thresholds.

## ℹ️ Table Information

- **Table ID:** 117
- **UUID:** 0ED7579A95D51547A48FD7693363C503
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:17Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| FirstRealTimeID | `Long Integer` | - | - |
| LastRealTimeID | `Long Integer` | - | - |
| WorksOrder | `Long Integer` | - | - |
| Acknowledged | `Boolean` | 🚫 Not Null | - |
| StaffID | `Long Integer` | - | - |
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

## 🔗 Related Items

### 📦 Classes

- [RealTimeSensorExceptionsEntity](../Classes/RealTimeSensorExceptionsEntity.md) - ORDA Entity class for RealTimeSensorExceptions table
- [RealTimeSensorExceptionsSelection](../Classes/RealTimeSensorExceptionsSelection.md) - ORDA EntitySelection class for RealTimeSensorExceptions table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:17Z*
