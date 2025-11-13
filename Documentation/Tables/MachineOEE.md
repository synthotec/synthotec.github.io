---
layout : default
title : MachineOEE
parent : Tables
---
# MachineOEE

📊 **Overview:** 13 Fields | 3 Indexes

## ℹ️ Table Information

- **Table ID:** 89
- **UUID:** EDFCD4019448A2478EF7BDE89DD8498C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:24Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (3)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ProductionDate | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| Availability | `Boolean` | 🚫 Not Null | - |
| Performance | `Boolean` | 🚫 Not Null | - |
| Quality | `Boolean` | 🚫 Not Null | - |
| OEE | `Boolean` | 🚫 Not Null | - |
| GoodTime | `Boolean` | 🚫 Not Null | - |
| PlannedTime | `Boolean` | 🚫 Not Null | - |
| TargetTime | `Boolean` | - | - |
| ActualTime | `Boolean` | 🚫 Not Null | - |
| TotalPacked | `Undefined` | - | - |
| TotalMade | `Undefined` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ProductionDate

**Properties:**

- **Type:** Integer
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

#### OEE

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### GoodTime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### PlannedTime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TargetTime

**Properties:**

- **Type:** Boolean

---

#### ActualTime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TotalPacked

**Properties:**

- **Type:** Undefined

---

#### TotalMade

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `WorksOrder` | Keywords | regular | - |
| `ProductionDate` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductionDate`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:24Z*
