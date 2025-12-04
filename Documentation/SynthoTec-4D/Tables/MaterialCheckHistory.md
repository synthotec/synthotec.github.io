---
layout : default
title : MaterialCheckHistory
parent : Tables
---
# MaterialCheckHistory

📊 **Overview:** 11 Fields | 6 Indexes | 5 Many-to-One Relations

## 📝 Description

🗨️ Transaction table recording material inspection results and quality checks. Links to Material batches with test data and approval status.

## ℹ️ Table Information

- **Table ID:** 39
- **UUID:** CD2B15382AF9D24BB806CE53302773A9
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:34:04Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (11)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (5)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| WorksOrder | `Long Integer` | 🚫 Not Null | - |
| MaterialID | `Long Integer` | 🚫 Not Null | - |
| Regrind | `Boolean` | 🚫 Not Null | - |
| CheckedBy | `String` (255) | 🚫 Not Null | - |
| DateTime | `String` (255) | 🚫 Not Null | - |
| CheckComment | `String` (255) | 🚫 Not Null | - |
| RMC1 | `Long Integer` | 🚫 Not Null | - |
| RMC2 | `Long Integer` | 🚫 Not Null | - |
| RMC3 | `Long Integer` | 🚫 Not Null | - |
| FromSharedSource | `Boolean` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `RMC1` | Keywords | regular | - |
| `RMC2` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `WorksOrder` | Keywords | regular | - |
| `RMC3` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active | - |
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active | - |
| `RMCEntity1` | [RMC](RMC.md) | `RMC1` → `RMCNo_l` | Active | - |
| `RMCEntity2` | [RMC](RMC.md) | `RMC2` → `RMCNo_l` | Active | - |
| `RMCEntity3` | [RMC](RMC.md) | `RMC3` → `RMCNo_l` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [MaterialCheck](../Forms/MaterialCheck.md) - Data source for MaterialCheck form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:34:04Z*
