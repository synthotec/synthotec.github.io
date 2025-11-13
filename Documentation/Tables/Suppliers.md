---
layout : default
title : Suppliers
parent : Tables
---
# Suppliers

📊 **Overview:** 25 Fields | 3 Indexes | 3 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 18
- **UUID:** DD48C27A4EEF9442A7DB4C93B8CD90D3
- **Primary Key:** 🔑 `SupplierID_l`
- **Generated:** 🕐 2025-11-13T02:47:54Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (25)
- [🔍 Indexes](#-indexes) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (3)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **SupplierID_l** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null, ��� Not Modifiable | - |
| Name_s | `String` (31) | ⚠️ Required, 🚫 Not Null | - |
| Address1_s | `String` (41) | 🚫 Not Null | - |
| Address2_s | `String` (41) | 🚫 Not Null | - |
| Address3_s | `String` (41) | 🚫 Not Null | - |
| County_s | `String` (21) | 🚫 Not Null | - |
| Postcode_s | `String` (11) | 🚫 Not Null | - |
| TelephoneNo_s | `String` (15) | 🚫 Not Null | - |
| FaxNo_s | `String` (21) | 🚫 Not Null | - |
| AccountsCode_s | `String` (5) | 🚫 Not Null | - |
| TypeOfSupply_s | `String` (25) | 🚫 Not Null | - |
| AdditionalInfo_txt | `String` | 🚫 Not Null | - |
| ContactName_s | `String` (31) | 🚫 Not Null | - |
| EMailAddress_s | `String` (51) | 🚫 Not Null | - |
| ConfirmationR | `Real` | 🚫 Not Null | - |
| FaxNo2_s | `String` (30) | 🚫 Not Null | - |
| EMailAddress2_s | `String` (51) | 🚫 Not Null | - |
| Position_s | `String` (21) | 🚫 Not Null | - |
| Archived_b | `Real` | 🚫 Not Null | - |
| ContactName2_s | `String` (21) | 🚫 Not Null | - |
| VATRate_r | `Boolean` | 🚫 Not Null | - |
| TelephneNo1_s | `String` (15) | 🚫 Not Null | - |
| LastOrdered | `Integer` | 🚫 Not Null | - |
| ApprovalStatus | `String` (255) | 🚫 Not Null | - |
| CofaEmailContact | `String` (255) | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Name_s` | Keywords | regular | - |
| `Archived_b` | Keywords | regular | - |
| `SupplierID_l` | Keywords | regular | ✨ Yes |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `SuppliesSelection` | [Supplies](Supplies.md) | `SupplierID_l` → `SupplierID_l` | Active | - |
| `PurchasesSelection` | [Purchases](Purchases.md) | `SupplierID_l` → `SupplierID_l` | Active | - |
| `SupplierDocumentationSelection` | [SupplierDocumentation](SupplierDocumentation.md) | `SupplierID` → `SupplierID_l` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [SuppliersEntity](../Classes/SuppliersEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:47:54Z*
