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
- **Generated:** 🕐 2025-11-13T02:35:13Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (24)
- [🔍 Indexes](#-indexes) (8)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

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

### Detailed Information

#### 🔑 UniqueID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, ⚠️ Mandatory, 🚫 Never Null

---

#### OrderNo_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SuppliesID_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Currency_s

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### Reference_s

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Description_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Quantity_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Unit_s

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Price_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### PriceQuantity_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Cost_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### FontStyle_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### FontSize_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### QuantityReceived_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### QuantityInvoiced_r

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

#### InvoiceNumber

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### DateRequested

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### NominalCode

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Revision

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### CAPEX

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Invoice

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### DateReceived

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

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

### Detailed Information

- **Field:** `OrderNo_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `UniqueID_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Invoiced`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `SuppliesID_i`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Description_txt`
  - **Kind:** keywords
  - **Type:** Cluster
- **Field:** `Received`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `DateRequested`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Description_txt`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `PurchasesEntity` | [Purchases](Purchases.md) | `OrderNo_l` → `OrderNo_l` | Active |
| `SuppliesEntity` | [Supplies](Supplies.md) | `SuppliesID_i` → `UniqueID_i` | Active |
| `NominalCodesEntity` | [NominalCodes](NominalCodes.md) | `NominalCode` → `ID` | Active |

### Detailed Information

#### PurchasesEntity

**Links to:** [Purchases](Purchases.md)

- **Source Field:** `OrderNo_l`
- **Destination Field:** `OrderNo_l`
- **State:** Active

---

#### SuppliesEntity

**Links to:** [Supplies](Supplies.md)

- **Source Field:** `SuppliesID_i`
- **Destination Field:** `UniqueID_i`
- **State:** Active

---

#### NominalCodesEntity

**Links to:** [NominalCodes](NominalCodes.md)

- **Source Field:** `NominalCode`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `PurchaseReceiptsSelection` | [PurchaseReceipts](PurchaseReceipts.md) | `PurchaseInfoID` → `UniqueID_l` | Active |
| `RMCSelection` | [RMC](RMC.md) | `PurchaseInfoID` → `UniqueID_l` | Active |

### Detailed Information

#### PurchaseReceiptsSelection

**Links from:** [PurchaseReceipts](PurchaseReceipts.md)

- **Source Table:** `PurchaseReceipts`
- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** Active

---

#### RMCSelection

**Links from:** [RMC](RMC.md)

- **Source Table:** `RMC`
- **Source Field:** `PurchaseInfoID`
- **This Table Field:** `UniqueID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:13Z*
