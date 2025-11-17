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
- **Generated:** 🕐 2025-11-13T23:19:47Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

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

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Customer` | Keywords | regular | - |
| `PickedNotificationSent` | Keywords | regular | - |
| `ReadyToPick` | Keywords | regular | - |
| `Type` | Keywords | regular | - |
| `Processed` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `AdviceNoteID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active | - |
| `Advice_NoteEntity` | [Advice_Note](Advice_Note.md) | `AdviceNoteID` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `OrderPickRequestSelection` | [OrderPickRequest](OrderPickRequest.md) | `PickRequestID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [PickRequest](../Classes/PickRequest.md) - ORDA DataClass class for PickRequest table
- [PickRequestEntity](../Classes/PickRequestEntity.md) - ORDA Entity class for PickRequest table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:47Z*
