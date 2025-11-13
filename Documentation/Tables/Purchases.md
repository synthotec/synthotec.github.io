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
- **Generated:** 🕐 2025-11-13T02:35:12Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 OrderNo_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, ⚠️ Mandatory, 🚫 Never Null

---

#### DateRaised_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Confirmed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RaisedBy_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### SupplierID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### GoodsReceived_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### InvoiceAuthorised_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### AdditionalInfo_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Archived_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### VATRate_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Received

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Invoiced

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Approved

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ApprovedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ApprovalRequested

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### OrderPrinted

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Revision

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### ApprovedDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `OrderNo_l` | Keywords | regular | ✨ Yes |
| `SupplierID_l` | Keywords | regular | - |
| `Archived_b` | Keywords | regular | - |

### Detailed Information

- **Field:** `OrderNo_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `SupplierID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Archived_b`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `SuppliersEntity` | [Suppliers](Suppliers.md) | `SupplierID_l` → `SupplierID_l` | Active |

### Detailed Information

#### SuppliersEntity

**Links to:** [Suppliers](Suppliers.md)

- **Source Field:** `SupplierID_l`
- **Destination Field:** `SupplierID_l`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `OrderNo_l` → `OrderNo_l` | Active |

### Detailed Information

#### PurchaseInfoSelection

**Links from:** [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `OrderNo_l`
- **This Table Field:** `OrderNo_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:12Z*
