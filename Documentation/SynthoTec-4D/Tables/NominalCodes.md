---
layout : default
title : NominalCodes
parent : Tables
---
# NominalCodes

📊 **Overview:** 6 Fields | 3 Indexes | 1 One-to-Many Relations

## 📝 Description

🗨️ Accounting lookup table defining general ledger codes for financial transactions. Used to categorize costs and revenue by account type.

## ℹ️ Table Information

- **Table ID:** 84
- **UUID:** B4B021F72621A44A861BDFF8762EE00C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:46Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| NominalCode | `Long Integer` | ✨ Unique | - |
| Description | `String` (255) | 🚫 Not Null | - |
| Code_4D | `String` (255) | 🚫 Not Null | - |
| Category | `String` (255) | 🚫 Not Null | - |
| FinishedGoodsTransport | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `FinishedGoodsTransport` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `NominalCode` | B-Tree | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `NominalCode` → `ID` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [CurrentDownTime](../Forms/CurrentDownTime.md) - Data source for CurrentDownTime form
- [Form1](../Forms/Form1.md) - Data source for Form1 form
- [NominalCodes](../Forms/NominalCodes.md) - Data source for NominalCodes form
- [PurchaseOrders](../Forms/PurchaseOrders.md) - Data source for PurchaseOrders form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:46Z*
