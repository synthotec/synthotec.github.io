---
layout : default
title : PickRequest
parent : Tables
---
# PickRequest

📊 **Overview:** 8 Fields | 7 Indexes | 2 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 123
- **UUID:** 6D98803393505545A137D7224E5DC09F
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:54Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Customer | `String` (255) | - | - |
| DespatchDate | `Integer` | - | - |
| Processed | `Real` | 🚫 Not Null | - |
| ReadyToPick | `Real` | 🚫 Not Null | - |
| AdviceNoteID | `Date` | - | - |
| Type | `Picture` | - | - |
| PickedNotificationSent | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Customer

**Properties:**

- **Type:** String (max length: 255)

---

#### DespatchDate

**Properties:**

- **Type:** Integer

---

#### Processed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ReadyToPick

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AdviceNoteID

**Properties:**

- **Type:** Date

---

#### Type

**Properties:**

- **Type:** Picture

---

#### PickedNotificationSent

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Customer` | Keywords | regular | - |
| `PickedNotificationSent` | Keywords | regular | - |
| `ReadyToPick` | Keywords | regular | - |
| `Type` | Keywords | regular | - |
| `Processed` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `AdviceNoteID` | Keywords | regular | - |

### Detailed Information

- **Field:** `Customer`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PickedNotificationSent`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ReadyToPick`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Type`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Processed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `AdviceNoteID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active |
| `Advice_NoteEntity` | [Advice_Note](Advice_Note.md) | `AdviceNoteID` → `ID` | Active |

### Detailed Information

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

#### Advice_NoteEntity

**Links to:** [Advice_Note](Advice_Note.md)

- **Source Field:** `AdviceNoteID`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `OrderPickRequestSelection` | [OrderPickRequest](OrderPickRequest.md) | `PickRequestID` → `ID` | Active |

### Detailed Information

#### OrderPickRequestSelection

**Links from:** [OrderPickRequest](OrderPickRequest.md)

- **Source Table:** `OrderPickRequest`
- **Source Field:** `PickRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:54Z*
