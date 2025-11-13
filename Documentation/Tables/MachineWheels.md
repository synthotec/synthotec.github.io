---
layout : default
title : MachineWheels
parent : Tables
---
# MachineWheels

📊 **Overview:** 28 Fields | 2 Indexes

## ℹ️ Table Information

- **Table ID:** 52
- **UUID:** 4E54F86DE90F56408B41789A54462C64
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:50Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (28)
- [🔍 Indexes](#-indexes) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Machine | `Picture` | 🚫 Not Null | - |
| AvgDailyHours | `Boolean` | 🚫 Not Null | - |
| MonHours | `Boolean` | 🚫 Not Null | - |
| TueHours | `Boolean` | 🚫 Not Null | - |
| WedHours | `Boolean` | 🚫 Not Null | - |
| ThursHours | `Boolean` | 🚫 Not Null | - |
| FriHours | `Boolean` | 🚫 Not Null | - |
| SatHours | `Boolean` | 🚫 Not Null | - |
| SunHours | `Boolean` | 🚫 Not Null | - |
| Weekend | `Real` | 🚫 Not Null | - |
| DaysLate | `Date` | 🚫 Not Null | - |
| DaysEarly | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| RemainingHours | `Boolean` | 🚫 Not Null | - |
| AutoStatus | `Real` | 🚫 Not Null | - |
| SlowStatus | `Real` | 🚫 Not Null | - |
| MouldStatus | `String` (255) | 🚫 Not Null | - |
| TimeOpened | `String` (255) | 🚫 Not Null | - |
| TimeClosed | `String` (255) | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| Availability | `Boolean` | 🚫 Not Null | - |
| Performance | `Boolean` | 🚫 Not Null | - |
| Quality | `Boolean` | 🚫 Not Null | - |
| LastAudit | `String` (255) | 🚫 Not Null | - |
| StopCycleID | `Date` | 🚫 Not Null | - |
| NextJobID | `Date` | 🚫 Not Null | - |
| AwaitingSetter | `Picture` | 🚫 Not Null | - |
| Priority | `Real` | 🚫 Not Null | - |

### Detailed Information

#### Machine

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### AvgDailyHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### MonHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TueHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### WedHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### ThursHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### FriHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### SatHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### SunHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Weekend

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DaysLate

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DaysEarly

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### RemainingHours

**Properties:**

- **Type:** Boolean
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

#### MouldStatus

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### TimeOpened

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### TimeClosed

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

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

#### StopCycleID

**Properties:**

- **Type:** Date
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

#### Priority

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Machine` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:50Z*
