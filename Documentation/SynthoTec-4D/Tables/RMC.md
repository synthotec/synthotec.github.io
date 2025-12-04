---
layout : default
title : RMC
parent : Tables
---
# RMC

📊 **Overview:** 12 Fields | 4 Indexes | 2 Many-to-One Relations | 6 One-to-Many Relations

## 📝 Description

🗨️ Transaction table for Raw Material Certificates tracking material certifications and test results. Links material batches to supplier certificates and quality data.

## ℹ️ Table Information

- **Table ID:** 27
- **UUID:** 888FFBDAC9DEBA469795A94E15901BAE
- **Primary Key:** 🔑 `RMCNo_l`
- **Generated:** 🕐 2025-12-04T14:33:53Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (6)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **RMCNo_l** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| MaterialID_l | `Long Integer` | 🚫 Not Null | - |
| RMCDate_d | `Date` | 🚫 Not Null | - |
| BatchNo_s | `String` (25) | 🚫 Not Null | - |
| Quantity_l | `Long Integer` | 🚫 Not Null | - |
| OrderNo_l | `Long Integer` | 🚫 Not Null | - |
| Name_s | `String` (30) | 🚫 Not Null | - |
| Remarks_s | `String` (20) | 🚫 Not Null | - |
| CofA_BLOB | `BLOB Scalar` | 🚫 Not Null | - |
| CofA_Filename | `String` (255) | 🚫 Not Null | - |
| CofA_Requested | `Date` | 🚫 Not Null | - |
| PurchaseInfoID | `Long Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `MaterialID_l` | Keywords | regular | - |
| `PurchaseInfoID` | Keywords | regular | - |
| `RMCNo_l` | Keywords | regular | ✨ Yes |
| `RMCDate_d` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID_l` → `Unique_ID` | Active | - |
| `PurchaseInfoEntity` | [PurchaseInfo](PurchaseInfo.md) | `PurchaseInfoID` → `UniqueID_l` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PurchaseReceiptsSelection` | [PurchaseReceipts](PurchaseReceipts.md) | `RMC` → `RMCNo_l` | Active | - |
| `MaterialStockTakeSelection` | [MaterialStockTake](MaterialStockTake.md) | `RMC` → `RMCNo_l` | Active | - |
| `MaterialCheckHistorySelection1` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC1` → `RMCNo_l` | Active | - |
| `MaterialCheckHistorySelection2` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC2` → `RMCNo_l` | Active | - |
| `MaterialCheckHistorySelection3` | [MaterialCheckHistory](MaterialCheckHistory.md) | `RMC3` → `RMCNo_l` | Active | - |
| `MaterialStockSelection` | [MaterialStock](MaterialStock.md) | `RMC` → `RMCNo_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [RMCEntity](../Classes/RMCEntity.md) - ORDA Entity class for RMC table

### 📄 Forms

- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:33:53Z*
