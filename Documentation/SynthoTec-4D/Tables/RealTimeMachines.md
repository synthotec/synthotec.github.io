---
layout : default
title : RealTimeMachines
parent : Tables
---
# RealTimeMachines

📊 **Overview:** 32 Fields | 2 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 63
- **UUID:** 475BE219B3D798439D301555A3D28CCC
- **Primary Key:** 🔑 `Machine`
- **Generated:** 🕐 2025-12-03T16:24:11Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (32)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (6)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| RequiresRecalculation | `Boolean` | 🚫 Not Null | - |
| 🔑 **Machine** | `Long Integer` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| MouldStatus | `String` (255) | 🚫 Not Null | - |
| LastActivity | `String` (255) | 🚫 Not Null | - |
| AutoStatus | `Boolean` | 🚫 Not Null | - |
| SlowStatus | `Boolean` | 🚫 Not Null | - |
| Battery | `Integer` | 🚫 Not Null | - |
| UpTime | `String` (255) | 🚫 Not Null | - |
| LastPulse | `String` (255) | 🚫 Not Null | - |
| LastCycleSensorData | `Object` | - | - |
| Availability | `Real` | 🚫 Not Null | - |
| Performance | `Real` | 🚫 Not Null | - |
| Quality | `Real` | 🚫 Not Null | - |
| LastAudit | `String` (255) | 🚫 Not Null | - |
| StopReason | `String` (255) | 🚫 Not Null | - |
| NextJobID | `Long Integer` | 🚫 Not Null | - |
| AwaitingSetter | `Integer` | 🚫 Not Null | - |
| PowerStatus | `Boolean` | 🚫 Not Null | - |
| MouldClosed | `Boolean` | 🚫 Not Null | - |
| WinVer | `String` (255) | 🚫 Not Null | - |
| MadeQty | `Long Integer` | 🚫 Not Null | - |
| TimeLeft | `Integer` | 🚫 Not Null | - |
| Cycle | `Real` | 🚫 Not Null | - |
| RealMade | `Long Integer` | 🚫 Not Null | - |
| Enabled | `Boolean` | 🚫 Not Null | - |
| Robot | `Boolean` | 🚫 Not Null | - |
| NoWorksOrderEmailSent | `Boolean` | 🚫 Not Null | - |
| TimeStartedNonRobot | `String` (255) | 🚫 Not Null | - |
| DownReason | `Long Integer` | - | - |
| TemperatureSensorException | `Boolean` | 🚫 Not Null | - |
| TemperatureSensors | `Object` | - | - |
| LastCycleTime | `Real` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Enabled` | Keywords | regular | - |
| `Machine` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `DownReasonsEntity` | [DownReasons](DownReasons.md) | `DownReason` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [RealTimeMachines](../Classes/RealTimeMachines.md) - ORDA DataClass class for RealTimeMachines table
- [RealTimeMachinesEntity](../Classes/RealTimeMachinesEntity.md) - ORDA Entity class for RealTimeMachines table

### 📄 Forms

- [CurrentDownTime](../Forms/CurrentDownTime.md) - Data source for CurrentDownTime form
- [DownTime](../Forms/DownTime.md) - Data source for DownTime form
- [MachineMaintenance](../Forms/MachineMaintenance.md) - Data source for MachineMaintenance form
- [RealTimeMonitor](../Forms/RealTimeMonitor.md) - Data source for RealTimeMonitor form
- [RealTimeViewer](../Forms/RealTimeViewer.md) - Data source for RealTimeViewer form
- [ShiftSummaries](../Forms/ShiftSummaries.md) - Data source for ShiftSummaries form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:24:11Z*
