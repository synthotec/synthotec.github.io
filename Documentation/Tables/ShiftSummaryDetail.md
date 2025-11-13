---
layout : default
title : ShiftSummaryDetail
parent : Tables
---
# ShiftSummaryDetail

📊 **Overview:** 6 Fields | 2 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 130
- **UUID:** 72508DC4C8B6954DB9CFBCAC2709E212
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:22Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (2)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Date` | - | - |
| RealTimeOutputMachine | `Unknown (21)` | - | - |
| Commentary | `String` | - | - |
| ShiftSummaryID | `Date` | - | - |
| DowntimeSincePrevious | `Long Integer` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### WorksOrder

**Properties:**

- **Type:** Date

---

#### RealTimeOutputMachine

**Properties:**

- **Type:** Unknown (21)

---

#### Commentary

**Properties:**

- **Type:** String

---

#### ShiftSummaryID

**Properties:**

- **Type:** Date

---

#### DowntimeSincePrevious

**Properties:**

- **Type:** Long Integer

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `WorksOrder` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ShiftSummaryEntity` | [ShiftSummary](ShiftSummary.md) | `ShiftSummaryID` → `ID` | Active |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |

### Detailed Information

#### ShiftSummaryEntity

**Links to:** [ShiftSummary](ShiftSummary.md)

- **Source Field:** `ShiftSummaryID`
- **Destination Field:** `ID`
- **State:** Active

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:37:22Z*
