---
layout : default
title : Purchases
parent : Tables
---
# Purchases

📊 **Overview:** 18 Fields | 3 Indexes | 1 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 21
- **UUID:** 0816EE7668E03647A01F7EB009589E04
- **Primary Key:** 🔑 `OrderNo_l`
- **Generated:** 🕐 2025-12-03T16:23:34Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)
  - [Forms](#-forms) (6)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **OrderNo_l** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | - |
| DateRaised_d | `Date` | 🚫 Not Null | - |
| Confirmed | `Boolean` | 🚫 Not Null | - |
| RaisedBy_s | `String` (30) | 🚫 Not Null | - |
| SupplierID_l | `Long Integer` | 🚫 Not Null | - |
| GoodsReceived_b | `Boolean` | 🚫 Not Null | - |
| InvoiceAuthorised_b | `Boolean` | 🚫 Not Null | - |
| AdditionalInfo_txt | `String` | 🚫 Not Null | - |
| Archived_b | `Boolean` | 🚫 Not Null | - |
| VATRate_r | `Real` | 🚫 Not Null | - |
| Received | `Boolean` | 🚫 Not Null | - |
| Invoiced | `Boolean` | 🚫 Not Null | - |
| Approved | `Boolean` | 🚫 Not Null | - |
| ApprovedBy | `String` (255) | 🚫 Not Null | - |
| ApprovalRequested | `Boolean` | 🚫 Not Null | - |
| OrderPrinted | `Boolean` | 🚫 Not Null | - |
| Revision | `Integer` | 🚫 Not Null | - |
| ApprovedDate | `Date` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `OrderNo_l` | Keywords | regular | ✨ Yes |
| `SupplierID_l` | Keywords | regular | - |
| `Archived_b` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `SuppliersEntity` | [Suppliers](Suppliers.md) | `SupplierID_l` → `SupplierID_l` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `OrderNo_l` → `OrderNo_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [PurchasesEntity](../Classes/PurchasesEntity.md) - ORDA Entity class for Purchases table

### 📄 Forms

- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialCalendar](../Forms/MaterialCalendar.md) - Data source for MaterialCalendar form
- [PurchaseOrders](../Forms/PurchaseOrders.md) - Data source for PurchaseOrders form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [SupplierManager](../Forms/SupplierManager.md) - Data source for SupplierManager form
- [ToolDisplay4](../Forms/ToolDisplay4.md) - Data source for ToolDisplay4 form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:34Z*
