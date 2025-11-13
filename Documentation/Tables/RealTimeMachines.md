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
- **Generated:** 🕐 2025-11-13T16:08:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (32)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| RequiresRecalculation | `Real` | 🚫 Not Null | - |
| 🔑 **Machine** | `Date` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| MouldStatus | `String` (255) | 🚫 Not Null | - |
| LastActivity | `String` (255) | 🚫 Not Null | - |
| AutoStatus | `Real` | 🚫 Not Null | - |
| SlowStatus | `Real` | 🚫 Not Null | - |
| Battery | `Picture` | 🚫 Not Null | - |
| UpTime | `String` (255) | 🚫 Not Null | - |
| LastPulse | `String` (255) | 🚫 Not Null | - |
| LastCycleSensorData | `Object` | - | - |
| Availability | `Boolean` | 🚫 Not Null | - |
| Performance | `Boolean` | 🚫 Not Null | - |
| Quality | `Boolean` | 🚫 Not Null | - |
| LastAudit | `String` (255) | 🚫 Not Null | - |
| StopReason | `String` (255) | 🚫 Not Null | - |
| NextJobID | `Date` | 🚫 Not Null | - |
| AwaitingSetter | `Picture` | 🚫 Not Null | - |
| PowerStatus | `Real` | 🚫 Not Null | - |
| MouldClosed | `Real` | 🚫 Not Null | - |
| WinVer | `String` (255) | 🚫 Not Null | - |
| MadeQty | `Date` | 🚫 Not Null | - |
| TimeLeft | `Undefined` | 🚫 Not Null | - |
| Cycle | `Boolean` | 🚫 Not Null | - |
| RealMade | `Date` | 🚫 Not Null | - |
| Enabled | `Real` | 🚫 Not Null | - |
| Robot | `Real` | 🚫 Not Null | - |
| NoWorksOrderEmailSent | `Real` | 🚫 Not Null | - |
| TimeStartedNonRobot | `String` (255) | 🚫 Not Null | - |
| DownReason | `Date` | - | - |
| TemperatureSensorException | `Real` | 🚫 Not Null | - |
| TemperatureSensors | `Object` | - | - |
| LastCycleTime | `Boolean` | - | - |

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

- [RealTimeMachines](../Classes/RealTimeMachines.md) - DataClass class
- [RealTimeMachinesEntity](../Classes/RealTimeMachinesEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:08:45Z*
