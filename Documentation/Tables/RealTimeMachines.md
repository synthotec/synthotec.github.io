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
- **Generated:** 🕐 2025-11-13T02:36:00Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (32)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

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
| LastCycleSensorData | `Unknown (21)` | - | - |
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
| TemperatureSensors | `Unknown (21)` | - | - |
| LastCycleTime | `Boolean` | - | - |

### Detailed Information

#### RequiresRecalculation

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### 🔑 Machine

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, 🚫 Never Null

---

#### MouldStatus

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### LastActivity

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### AutoStatus

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### SlowStatus

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Battery

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### UpTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### LastPulse

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### LastCycleSensorData

**Properties:**

- **Type:** Unknown (21)

---

#### Availability

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Performance

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Quality

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### LastAudit

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### StopReason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### NextJobID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### AwaitingSetter

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### PowerStatus

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### MouldClosed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### WinVer

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MadeQty

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### TimeLeft

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### Cycle

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### RealMade

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Enabled

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Robot

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NoWorksOrderEmailSent

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### TimeStartedNonRobot

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### DownReason

**Properties:**

- **Type:** Date

---

#### TemperatureSensorException

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### TemperatureSensors

**Properties:**

- **Type:** Unknown (21)

---

#### LastCycleTime

**Properties:**

- **Type:** Boolean

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Enabled` | Keywords | regular | - |
| `Machine` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Enabled`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `DownReasonsEntity` | [DownReasons](DownReasons.md) | `DownReason` → `ID` | Active |

### Detailed Information

#### DownReasonsEntity

**Links to:** [DownReasons](DownReasons.md)

- **Source Field:** `DownReason`
- **Destination Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:00Z*
