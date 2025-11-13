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
- **Generated:** 🕐 2025-11-13T02:35:55Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| SensorData | `Unknown (21)` | - | - |
| EndDate | `Integer` | 🚫 Not Null | - |
| EndTime | `Long Integer` | 🚫 Not Null | - |
| CycleTime | `Boolean` | 🚫 Not Null | - |
| Stoppage | `Real` | 🚫 Not Null | - |
| Impressions | `Picture` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| MouldClosedTime | `Boolean` | 🚫 Not Null | - |
| DownReason | `Date` | - | - |
| Robot | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### SensorData

**Properties:**

- **Type:** Unknown (21)

---

#### EndDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### EndTime

**Properties:**

- **Type:** Long Integer
- **Constraints:** 🚫 Never Null

---

#### CycleTime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Stoppage

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Impressions

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MouldClosedTime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### DownReason

**Properties:**

- **Type:** Date

---

#### Robot

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Stoppage` | Cluster | regular | - |
| `ID` | B-Tree | regular | ✨ Yes |
| `Robot` | Cluster | regular | - |
| `WorksOrder` | Cluster | regular | - |
| `EndDate` | Cluster | regular | - |
| `WorksOrder` | B-Tree | regular | - |
| `DownReason` | Keywords | regular | - |

### Detailed Information

- **Field:** `Stoppage`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `Robot`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `EndDate`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `DownReason`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |
| `DownReasonsEntity` | [DownReasons](DownReasons.md) | `DownReason` → `ID` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### DownReasonsEntity

**Links to:** [DownReasons](DownReasons.md)

- **Source Field:** `DownReason`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `FirstRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `FirstRealTimeID` → `ID` | Active |
| `LastRealTimeSensorExceptionsSelection` | [RealTimeSensorExceptions](RealTimeSensorExceptions.md) | `LastRealTimeID` → `ID` | Active |

### Detailed Information

#### FirstRealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `FirstRealTimeID`
- **This Table Field:** `ID`
- **State:** Active

---

#### LastRealTimeSensorExceptionsSelection

**Links from:** [RealTimeSensorExceptions](RealTimeSensorExceptions.md)

- **Source Table:** `RealTimeSensorExceptions`
- **Source Field:** `LastRealTimeID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:55Z*
