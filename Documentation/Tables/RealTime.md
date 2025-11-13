---
layout : default
title : RealTime
parent : Tables
---
# RealTime

📊 **Overview:** 11 Fields | 7 Indexes | 2 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 57
- **UUID:** B037623CFAEA3D4EB94D9916905B77FC
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:48:30Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| SensorData | `Object` | - | - |
| EndDate | `Integer` | 🚫 Not Null | - |
| EndTime | `Long Integer` | 🚫 Not Null | - |
| CycleTime | `Boolean` | 🚫 Not Null | - |
| Stoppage | `Real` | 🚫 Not Null | - |
| Impressions | `Picture` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| MouldClosedTime | `Boolean` | 🚫 Not Null | - |
| DownReason | `Date` | - | - |
| Robot | `Real` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Stoppage` | Cluster | regular | - |
| `ID` | B-Tree | regular | ✨ Yes |
| `Robot` | Cluster | regular | - |
| `WorksOrder` | Cluster | regular | - |
| `EndDate` | Cluster | regular | - |
| `WorksOrder` | B-Tree | regular | - |
| `DownReason` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `DownReasonsEntity` | [DownReasons](DownReasons.md) | `DownReason` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `FirstRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `FirstRealTimeID` → `ID` | Active | - |
| `LastRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `LastRealTimeID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [RealTime](../Classes/RealTime.md) - DataClass class
- [RealTimeEntity](../Classes/RealTimeEntity.md) - Entity class
- [RealTimeSelection](../Classes/RealTimeSelection.md) - EntitySelection class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:48:30Z*
