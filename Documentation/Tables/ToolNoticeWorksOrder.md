---
layout : default
title : ToolNoticeWorksOrder
parent : Tables
---
# ToolNoticeWorksOrder

📊 **Overview:** 4 Fields | 4 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 135
- **UUID:** 4B07FFB98BFE74459EB30ECE3B9D6E1F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:37:26Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| ToolNoticeID | `Date` | - | - |
| WorksOrder | `Date` | - | - |
| EmailSent | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### ToolNoticeID

**Properties:**

- **Type:** Date

---

#### WorksOrder

**Properties:**

- **Type:** Date

---

#### EmailSent

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ToolNoticeID` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `EmailSent` | Keywords | regular | - |

### Detailed Information

- **Field:** `ToolNoticeID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `EmailSent`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ToolNoticeEntity` | [ToolNotice](ToolNotice.md) | `ToolNoticeID` → `ToolID` | Active |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |

### Detailed Information

#### ToolNoticeEntity

**Links to:** [ToolNotice](ToolNotice.md)

- **Source Field:** `ToolNoticeID`
- **Destination Field:** `ToolID`
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
*Generated at: 2025-11-13T02:37:26Z*
