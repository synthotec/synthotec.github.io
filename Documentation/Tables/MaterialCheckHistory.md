---
layout : default
title : MaterialCheckHistory
parent : Tables
---
# MaterialCheckHistory

📊 **Overview:** 11 Fields | 6 Indexes | 5 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 39
- **UUID:** CD2B15382AF9D24BB806CE53302773A9
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:28Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (5)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| MaterialID | `Date` | 🚫 Not Null | - |
| Regrind | `Real` | 🚫 Not Null | - |
| CheckedBy | `String` (255) | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| CheckComment | `String` (255) | 🚫 Not Null | - |
| RMC1 | `Date` | 🚫 Not Null | - |
| RMC2 | `Date` | 🚫 Not Null | - |
| RMC3 | `Date` | 🚫 Not Null | - |
| FromSharedSource | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Regrind

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### CheckedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### DateTime

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CheckComment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### RMC1

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RMC2

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RMC3

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### FromSharedSource

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `RMC1` | Keywords | regular | - |
| `RMC2` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `WorksOrder` | Keywords | regular | - |
| `RMC3` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

### Detailed Information

- **Field:** `RMC1`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RMC2`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `RMC3`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MaterialID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active |
| `RMCEntity1` | [RMC](RMC.md) | `RMC1` → `RMCNo_l` | Active |
| `RMCEntity2` | [RMC](RMC.md) | `RMC2` → `RMCNo_l` | Active |
| `RMCEntity3` | [RMC](RMC.md) | `RMC3` → `RMCNo_l` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MaterialID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### RMCEntity1

**Links to:** [RMC](RMC.md)

- **Source Field:** `RMC1`
- **Destination Field:** `RMCNo_l`
- **State:** Active

---

#### RMCEntity2

**Links to:** [RMC](RMC.md)

- **Source Field:** `RMC2`
- **Destination Field:** `RMCNo_l`
- **State:** Active

---

#### RMCEntity3

**Links to:** [RMC](RMC.md)

- **Source Field:** `RMC3`
- **Destination Field:** `RMCNo_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:28Z*
