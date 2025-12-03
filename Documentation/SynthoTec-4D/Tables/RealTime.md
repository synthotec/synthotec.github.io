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
- **Generated:** 🕐 2025-12-03T16:24:05Z

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
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | Primary key, auto-incremented unique identifier. WARNING: Catalog shows type code 4 (Date) but this field is actually a Long Integer in the database schema. |
| SensorData | `Object` | - | JSON object containing raw sensor readings from manufacturing equipment. Stores structured sensor data including timestamps, values, and sensor identifiers. |
| EndDate | `Date` | 🚫 Not Null | Date when the production cycle ended. WARNING: Catalog shows type code 8 (Integer) but this field is actually a Date type in the database schema. |
| EndTime | `Time` | 🚫 Not Null | Time when the production cycle ended. WARNING: Catalog shows type code 9 (Long Integer) but this field is actually a Time type in the database schema. |
| CycleTime | `Real` | 🚫 Not Null | Duration of the production cycle. WARNING: Catalog shows type code 6 (Boolean) but this field is actually a Real/numeric type in the database schema. |
| Stoppage | `Boolean` | 🚫 Not Null | Boolean flag indicating whether the machine was stopped (true) or running (false) during this cycle. WARNING: Catalog shows type code 1 (Real) but this field is actually a Boolean type in the database schema. |
| Impressions | `Integer` | 🚫 Not Null | Number of parts produced (impressions) during this production cycle. WARNING: Catalog shows type code 3 (Picture) but this field is actually an Integer type in the database schema. |
| WorksOrder | `Long Integer` | 🚫 Not Null | Foreign key to WorksOrder table, links this real-time data to the production work order being executed. Cannot be null, indexed for performance. |
| MouldClosedTime | `Real` | 🚫 Not Null | Duration that the mould was closed during the production cycle. WARNING: Catalog shows type code 6 (Boolean) but this field is actually a Real/numeric type in the database schema. |
| DownReason | `Long Integer` | - | Foreign key to DownReasons table, identifies the reason for machine stoppage if a stoppage occurred. Can be null if no stoppage. Indexed with keywords for search. |
| Robot | `Boolean` | 🚫 Not Null | Boolean flag indicating whether robot was in use for this production cycle. WARNING: Catalog shows type code 1 (Real) but this field is actually a Boolean type in the database schema. |

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
*Generated at: 2025-12-03T16:24:05Z*
