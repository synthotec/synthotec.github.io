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
- **Generated:** 🕐 2025-11-13T02:36:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### FirstRealTimeID

**Properties:**

- **Type:** Date

---

#### LastRealTimeID

**Properties:**

- **Type:** Date

---

#### WorksOrder

**Properties:**

- **Type:** Date

---

#### Acknowledged

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### StaffID

**Properties:**

- **Type:** Date

---

#### Comment

**Properties:**

- **Type:** String (max length: 255)

---

#### RouteCards

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `WorksOrder` | Keywords | regular | - |
| `Acknowledged` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Acknowledged`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `FirstRealTimeEntity` | [RealTime](RealTime.md) | `FirstRealTimeID` → `ID` | Active |
| `LastRealTimeEntity` | [RealTime](RealTime.md) | `LastRealTimeID` → `ID` | Active |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |
| `StaffEntity` | [Staff](Staff.md) | `StaffID` → `StaffID` | Active |

### Detailed Information

#### FirstRealTimeEntity

**Links to:** [RealTime](RealTime.md)

- **Source Field:** `FirstRealTimeID`
- **Destination Field:** `ID`
- **State:** Active

---

#### LastRealTimeEntity

**Links to:** [RealTime](RealTime.md)

- **Source Field:** `LastRealTimeID`
- **Destination Field:** `ID`
- **State:** Active

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### StaffEntity

**Links to:** [Staff](Staff.md)

- **Source Field:** `StaffID`
- **Destination Field:** `StaffID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:49Z*
