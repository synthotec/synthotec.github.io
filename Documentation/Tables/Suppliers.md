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
- **Generated:** 🕐 2025-11-13T02:35:10Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (25)
- [🔍 Indexes](#-indexes) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (3)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **SupplierID_l** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
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

### Detailed Information

#### 🔑 SupplierID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null, 🔒 Not Modifiable

---

#### Name_s

**Properties:**

- **Type:** String (max length: 31)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Address1_s

**Properties:**

- **Type:** String (max length: 41)
- **Constraints:** 🚫 Never Null

---

#### Address2_s

**Properties:**

- **Type:** String (max length: 41)
- **Constraints:** 🚫 Never Null

---

#### Address3_s

**Properties:**

- **Type:** String (max length: 41)
- **Constraints:** 🚫 Never Null

---

#### County_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** 🚫 Never Null

---

#### Postcode_s

**Properties:**

- **Type:** String (max length: 11)
- **Constraints:** 🚫 Never Null

---

#### TelephoneNo_s

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### FaxNo_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** 🚫 Never Null

---

#### AccountsCode_s

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### TypeOfSupply_s

**Properties:**

- **Type:** String (max length: 25)
- **Constraints:** 🚫 Never Null

---

#### AdditionalInfo_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### ContactName_s

**Properties:**

- **Type:** String (max length: 31)
- **Constraints:** 🚫 Never Null

---

#### EMailAddress_s

**Properties:**

- **Type:** String (max length: 51)
- **Constraints:** 🚫 Never Null

---

#### ConfirmationR

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### FaxNo2_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### EMailAddress2_s

**Properties:**

- **Type:** String (max length: 51)
- **Constraints:** 🚫 Never Null

---

#### Position_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** 🚫 Never Null

---

#### Archived_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ContactName2_s

**Properties:**

- **Type:** String (max length: 21)
- **Constraints:** 🚫 Never Null

---

#### VATRate_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TelephneNo1_s

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### LastOrdered

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ApprovalStatus

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### CofaEmailContact

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Name_s` | Keywords | regular | - |
| `Archived_b` | Keywords | regular | - |
| `SupplierID_l` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Name_s`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Archived_b`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `SupplierID_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `SuppliesSelection` | [Supplies](Supplies.md) | `SupplierID_l` → `SupplierID_l` | Active |
| `PurchasesSelection` | [Purchases](Purchases.md) | `SupplierID_l` → `SupplierID_l` | Active |
| `SupplierDocumentationSelection` | [SupplierDocumentation](SupplierDocumentation.md) | `SupplierID` → `SupplierID_l` | Active |

### Detailed Information

#### SuppliesSelection

**Links from:** [Supplies](Supplies.md)

- **Source Table:** `Supplies`
- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** Active

---

#### PurchasesSelection

**Links from:** [Purchases](Purchases.md)

- **Source Table:** `Purchases`
- **Source Field:** `SupplierID_l`
- **This Table Field:** `SupplierID_l`
- **State:** Active

---

#### SupplierDocumentationSelection

**Links from:** [SupplierDocumentation](SupplierDocumentation.md)

- **Source Table:** `SupplierDocumentation`
- **Source Field:** `SupplierID`
- **This Table Field:** `SupplierID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:10Z*
