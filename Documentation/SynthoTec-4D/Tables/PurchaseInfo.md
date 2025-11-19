---
layout : default
title : PurchaseInfo
parent : Tables
---
# PurchaseInfo

📊 **Overview:** 24 Fields | 8 Indexes | 3 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 22
- **UUID:** C3FDC44293A15B4EA942AFEBF0341C9C
- **Primary Key:** 🔑 `UniqueID_l`
- **Generated:** 🕐 2025-11-13T23:18:02Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (24)
- [🔍 Indexes](#-indexes) (8)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (6)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **UniqueID_l** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | - |
| OrderNo_l | `Date` | 🚫 Not Null | - |
| SuppliesID_i | `Picture` | 🚫 Not Null | - |
| Currency_s | `String` (3) | 🚫 Not Null | - |
| Reference_s | `String` (20) | 🚫 Not Null | - |
| Description_txt | `String` | 🚫 Not Null | - |
| Quantity_r | `Boolean` | 🚫 Not Null | - |
| Unit_s | `String` (20) | 🚫 Not Null | - |
| Price_r | `Boolean` | 🚫 Not Null | - |
| PriceQuantity_l | `Date` | 🚫 Not Null | - |
| Cost_r | `Boolean` | 🚫 Not Null | - |
| FontStyle_i | `Picture` | 🚫 Not Null | - |
| FontSize_i | `Picture` | 🚫 Not Null | - |
| QuantityReceived_r | `Boolean` | 🚫 Not Null | - |
| QuantityInvoiced_r | `Boolean` | 🚫 Not Null | - |
| Received | `Real` | 🚫 Not Null | - |
| Invoiced | `Real` | 🚫 Not Null | - |
| InvoiceNumber | `String` (255) | 🚫 Not Null | - |
| DateRequested | `Integer` | 🚫 Not Null | - |
| NominalCode | `Date` | 🚫 Not Null | - |
| Revision | `Picture` | 🚫 Not Null | - |
| CAPEX | `Date` | 🚫 Not Null | - |
| Invoice | `String` (255) | 🚫 Not Null | - |
| DateReceived | `Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `OrderNo_l` | Keywords | regular | - |
| `UniqueID_l` | Keywords | regular | ✨ Yes |
| `Invoiced` | Keywords | regular | - |
| `SuppliesID_i` | Keywords | regular | - |
| `Description_txt` | Cluster | keywords | - |
| `Received` | Keywords | regular | - |
| `DateRequested` | Keywords | regular | - |
| `Description_txt` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `PurchasesEntity` | [Purchases](Purchases.md) | `OrderNo_l` → `OrderNo_l` | Active | - |
| `SuppliesEntity` | [Supplies](Supplies.md) | `SuppliesID_i` → `UniqueID_i` | Active | - |
| `NominalCodesEntity` | [NominalCodes](NominalCodes.md) | `NominalCode` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PurchaseReceiptsSelection` | [PurchaseReceipts](PurchaseReceipts.md) | `PurchaseInfoID` → `UniqueID_l` | Active | - |
| `RMCSelection` | [RMC](RMC.md) | `PurchaseInfoID` → `UniqueID_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [PurchaseInfoEntity](../Classes/PurchaseInfoEntity.md) - ORDA Entity class for PurchaseInfo table

### 📄 Forms

- [BOM_MaterialPrices](../Forms/BOM_MaterialPrices.md) - Data source for BOM_MaterialPrices form
- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [MaterialOutlook](../Forms/MaterialOutlook.md) - Data source for MaterialOutlook form
- [NominalCodes](../Forms/NominalCodes.md) - Data source for NominalCodes form
- [PurchaseOrders](../Forms/PurchaseOrders.md) - Data source for PurchaseOrders form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:18:02Z*
