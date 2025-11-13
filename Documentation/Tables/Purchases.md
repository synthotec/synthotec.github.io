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
- **Generated:** 🕐 2025-11-13T02:47:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **OrderNo_l** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | - |
| DateRaised_d | `Integer` | 🚫 Not Null | - |
| Confirmed | `Real` | 🚫 Not Null | - |
| RaisedBy_s | `String` (30) | 🚫 Not Null | - |
| SupplierID_l | `Date` | 🚫 Not Null | - |
| GoodsReceived_b | `Real` | 🚫 Not Null | - |
| InvoiceAuthorised_b | `Real` | 🚫 Not Null | - |
| AdditionalInfo_txt | `String` | 🚫 Not Null | - |
| Archived_b | `Real` | 🚫 Not Null | - |
| VATRate_r | `Boolean` | 🚫 Not Null | - |
| Received | `Real` | 🚫 Not Null | - |
| Invoiced | `Real` | 🚫 Not Null | - |
| Approved | `Real` | 🚫 Not Null | - |
| ApprovedBy | `String` (255) | 🚫 Not Null | - |
| ApprovalRequested | `Real` | 🚫 Not Null | - |
| OrderPrinted | `Real` | 🚫 Not Null | - |
| Revision | `Picture` | 🚫 Not Null | - |
| ApprovedDate | `Integer` | 🚫 Not Null | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:47:57Z*
