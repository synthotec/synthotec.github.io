---
layout : default
title : MaterialStock
parent : Tables
---
# MaterialStock

📊 **Overview:** 12 Fields | 7 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 48
- **UUID:** C11E4B61162CA04E8020762F66A8FC50
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (7)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| MaterialID | `Long Integer` | 🚫 Not Null | - |
| RMC | `Long Integer` | 🚫 Not Null | - |
| Location | `String` (255) | 🚫 Not Null | - |
| Quantity | `Real` | 🚫 Not Null | - |
| PalletNumber | `Long Integer` | 🚫 Not Null | - |
| MaterialName | `String` (255) | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| LastMoveDate | `Date` | 🚫 Not Null | - |
| Comment | `String` (125) | 🚫 Not Null | - |
| LocationID | `String` | - | - |
| LabelsPrinted | `Boolean` | - | - |
| SheetsPrinted | `Boolean` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `LabelsPrinted` | Keywords | regular | - |
| `LocationID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `PalletNumber` | Keywords | regular | - |
| `SheetsPrinted` | Keywords | regular | - |
| `RMC` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `MaterialEntity` | [Material](Material.md) | `MaterialID` → `Unique_ID` | Active | - |
| `RMCEntity` | [RMC](RMC.md) | `RMC` → `RMCNo_l` | Active | - |
| `LocationEntity` | [Location](Location.md) | `LocationID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [MaterialStock](../Classes/MaterialStock.md) - ORDA DataClass class for MaterialStock table
- [MaterialStockEntity](../Classes/MaterialStockEntity.md) - ORDA Entity class for MaterialStock table

### 📄 Forms

- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:57Z*
