---
layout : default
title : RealTime
parent : Tables
---
# RealTime

📊 **Overview:** 11 Fields | 7 Indexes | 2 Many-to-One Relations | 2 One-to-Many Relations

## 📝 Description

🗨️ Stores real-time machine sensor data and production cycle information from manufacturing equipment. Captures timestamped sensor readings, cycle times, stoppages, and work order linkage for production monitoring and analysis.

## ℹ️ Table Information

- **Table ID:** 57
- **UUID:** B037623CFAEA3D4EB94D9916905B77FC
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:19Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (3)
  - [Forms](#-forms) (6)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| SensorData | `Object` | - | - |
| EndDate | `Date` | 🚫 Not Null | - |
| EndTime | `Time` | 🚫 Not Null | - |
| CycleTime | `Real` | 🚫 Not Null | - |
| Stoppage | `Boolean` | 🚫 Not Null | - |
| Impressions | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| MouldClosedTime | `Real` | 🚫 Not Null | - |
| DownReason | `Long Integer` | - | - |
| Robot | `Boolean` | 🚫 Not Null | - |

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
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | Many-to-one relationship linking real-time data records to their parent work order. Allows querying all sensor data for a specific production job. |
| `DownReasonsEntity` | [DownReasons](DownReasons.md) | `DownReason` → `ID` | Active | Many-to-one relationship linking real-time records to the reason code for machine downtime. Optional relationship (only set when stoppage occurred). |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `FirstRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `FirstRealTimeID` → `ID` | Active | One-to-many relationship where this RealTime record is the first occurrence in a sensor exception range. Links to RealTimeSensorExceptions tracking anomalies. |
| `LastRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `LastRealTimeID` → `ID` | Active | One-to-many relationship where this RealTime record is the last occurrence in a sensor exception range. Links to RealTimeSensorExceptions tracking anomalies. |

## 🔗 Related Items

### 📦 Classes

- [RealTime](../Classes/RealTime.md) - ORDA DataClass class for RealTime table
- [RealTimeEntity](../Classes/RealTimeEntity.md) - ORDA Entity class for RealTime table
- [RealTimeSelection](../Classes/RealTimeSelection.md) - ORDA EntitySelection class for RealTime table

### 📄 Forms

- [ChangeRealTimeImpressions](../Forms/ChangeRealTimeImpressions.md) - Data source for ChangeRealTimeImpressions form
- [CycleHistory](../Forms/CycleHistory.md) - Data source for CycleHistory form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [RTSUM](../Forms/RTSUM.md) - Data source for RTSUM form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form
- [ToolTemps](../Forms/ToolTemps.md) - Data source for ToolTemps form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:19Z*
