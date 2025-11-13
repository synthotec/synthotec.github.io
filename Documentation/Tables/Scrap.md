---
layout : default
title : Scrap
parent : Tables
---
# Scrap

📊 **Overview:** 15 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 47
- **UUID:** B91E3A24E0704F41AAE38F93EE48B9E6
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:46Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (15)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| DateScrapped | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| DateProduced | `Integer` | 🚫 Not Null | - |
| Fault | `String` (255) | 🚫 Not Null | - |
| Reason | `String` (255) | 🚫 Not Null | - |
| Quantity | `Date` | 🚫 Not Null | - |
| Location | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| ScrappedBy | `String` (255) | 🚫 Not Null | - |
| New | `Real` | 🚫 Not Null | - |
| Shift | `Date` | 🚫 Not Null | - |
| Sequence | `Picture` | 🚫 Not Null | - |
| Comment | `String` (255) | 🚫 Not Null | - |
| DateTimeScrapped | `String` (255) | 🚫 Not Null | - |
| ShiftDate | `Date` | 🚫 Not Null | - |

### Detailed Information

#### DateScrapped

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DateProduced

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Fault

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Reason

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Location

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### ScrappedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### New

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Shift

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Sequence

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Comment

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### DateTimeScrapped

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ShiftDate

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ShiftDate` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ShiftDate`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:46Z*
