---
layout : default
title : ProductPackaging
parent : Tables
---
# ProductPackaging

📊 **Overview:** 9 Fields | 6 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 35
- **UUID:** A0DC125CC548024984CE4F807E2D45E2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:25Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ToolID | `Date` | 🚫 Not Null | - |
| SuppliesID | `Picture` | 🚫 Not Null | - |
| Quantity | `Boolean` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| CreatedBy | `String` (255) | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |
| Customer | `String` (255) | - | - |
| CustomerSpecific | `Real` | 🚫 Not Null | - |

### Detailed Information

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SuppliesID

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Quantity

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### CreatedBy

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MigrationID

**Properties:**

- **Type:** Date

---

#### Customer

**Properties:**

- **Type:** String (max length: 255)

---

#### CustomerSpecific

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `CustomerSpecific` | Keywords | regular | - |
| `Customer` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `ToolID` | Keywords | regular | - |
| `ProductID` | Keywords | regular | - |
| `SuppliesID` | Keywords | regular | - |

### Detailed Information

- **Field:** `CustomerSpecific`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `SuppliesID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `SuppliesEntity` | [Supplies](Supplies.md) | `SuppliesID` → `UniqueID_i` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |
| `CustomerEntity` | [Customer](Customer.md) | `Customer` → `Customer_Code` | Active |

### Detailed Information

#### SuppliesEntity

**Links to:** [Supplies](Supplies.md)

- **Source Field:** `SuppliesID`
- **Destination Field:** `UniqueID_i`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:25Z*
