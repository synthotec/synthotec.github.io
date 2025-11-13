---
layout : default
title : Advice_Note
parent : Tables
---
# Advice_Note

📊 **Overview:** 6 Fields | 2 Indexes | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 9
- **UUID:** 1C150D42AE7E4341870D4DBFA6AD3288
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:34:21Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Advice_Note_No | `Date` | ⚡ Auto, 🚫 Not Null | - |
| Customer_Code | `String` (3) | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| DespatchDate | `Integer` | - | - |
| ArrivalDate | `Integer` | - | - |
| Transport | `String` (255) | - | - |

### Detailed Information

#### Advice_Note_No

**Properties:**

- **Type:** Date
- **Constraints:** ⚡ Auto-sequence, 🚫 Never Null

---

#### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### DespatchDate

**Properties:**

- **Type:** Integer

---

#### ArrivalDate

**Properties:**

- **Type:** Integer

---

#### Transport

**Properties:**

- **Type:** String (max length: 255)

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `Advice_Note_No` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Advice_Note_No`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `CofCSelection` | [CofC](CofC.md) | `Advice_Note_No` → `Advice_Note_No` | Active |
| `PickRequestSelection` | [PickRequest](PickRequest.md) | `AdviceNoteID` → `ID` | Active |

### Detailed Information

#### CofCSelection

**Links from:** [CofC](CofC.md)

- **Source Table:** `CofC`
- **Source Field:** `Advice_Note_No`
- **This Table Field:** `Advice_Note_No`
- **State:** Active

---

#### PickRequestSelection

**Links from:** [PickRequest](PickRequest.md)

- **Source Table:** `PickRequest`
- **Source Field:** `AdviceNoteID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:21Z*
