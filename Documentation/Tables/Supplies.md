---
layout : default
title : Supplies
parent : Tables
---
# Supplies

📊 **Overview:** 19 Fields | 3 Indexes | 2 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 20
- **UUID:** B84FAAF4158D23479C7828325B99FDF5
- **Primary Key:** 🔑 `UniqueID_i`
- **Generated:** 🕐 2025-11-13T02:35:12Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (19)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **UniqueID_i** | `Picture` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | - |
| Name_s | `String` (31) | 🚫 Not Null | - |
| Ref_s | `String` (20) | 🚫 Not Null | - |
| Description_txt | `String` | 🚫 Not Null | - |
| Price_r | `Boolean` | 🚫 Not Null | - |
| PriceQuantity_l | `Date` | 🚫 Not Null | - |
| MinOrderQty_r | `Boolean` | 🚫 Not Null | - |
| SupplierID_l | `Date` | 🚫 Not Null | - |
| UnitOfSale_s | `String` (20) | 🚫 Not Null | - |
| StockQty_r | `Boolean` | 🚫 Not Null | - |
| AdditionalInfo_txt | `String` | 🚫 Not Null | - |
| Currency_s | `String` (3) | 🚫 Not Null | - |
| IsPackaging | `Real` | 🚫 Not Null | - |
| PackagingCat | `Date` | 🚫 Not Null | - |
| RawMaterial | `Real` | 🚫 Not Null | - |
| MaterialID | `Date` | 🚫 Not Null | - |
| ReuseTimes | `Picture` | 🚫 Not Null | - |
| MarginDeduction | `Real` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### 🔑 UniqueID_i

**Properties:**

- **Type:** Picture
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, ⚠️ Mandatory, 🚫 Never Null

---

#### Name_s

**Properties:**

- **Type:** String (max length: 31)
- **Constraints:** 🚫 Never Null

---

#### Ref_s

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### Description_txt

**Properties:**

- **Type:** String
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

#### MinOrderQty_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### SupplierID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### UnitOfSale_s

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** 🚫 Never Null

---

#### StockQty_r

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### AdditionalInfo_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Currency_s

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### IsPackaging

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### PackagingCat

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RawMaterial

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### MaterialID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ReuseTimes

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### MarginDeduction

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `UniqueID_i` | Keywords | regular | ✨ Yes |
| `MaterialID` | Keywords | regular | - |
| `SupplierID_l` | Keywords | regular | - |

### Detailed Information

- **Field:** `UniqueID_i` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MaterialID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `SupplierID_l`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `SuppliersEntity` | [Suppliers](Suppliers.md) | `SupplierID_l` → `SupplierID_l` | Active |
| `PackagingCatsEntity` | [PackagingCats](PackagingCats.md) | `PackagingCat` → `ID` | Active |

### Detailed Information

#### SuppliersEntity

**Links to:** [Suppliers](Suppliers.md)

- **Source Field:** `SupplierID_l`
- **Destination Field:** `SupplierID_l`
- **State:** Active

---

#### PackagingCatsEntity

**Links to:** [PackagingCats](PackagingCats.md)

- **Source Field:** `PackagingCat`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ProductPackagingSelection` | [ProductPackaging](ProductPackaging.md) | `SuppliesID` → `UniqueID_i` | Active |
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `SuppliesID_i` → `UniqueID_i` | Active |

### Detailed Information

#### ProductPackagingSelection

**Links from:** [ProductPackaging](ProductPackaging.md)

- **Source Table:** `ProductPackaging`
- **Source Field:** `SuppliesID`
- **This Table Field:** `UniqueID_i`
- **State:** Active

---

#### PurchaseInfoSelection

**Links from:** [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `SuppliesID_i`
- **This Table Field:** `UniqueID_i`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:12Z*
