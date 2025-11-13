---
layout : default
title : Product_Option
parent : Tables
---
# Product_Option

📊 **Overview:** 29 Fields | 8 Indexes | 4 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 13
- **UUID:** 2E835762FEA7484EB4687878631CFB10
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:02Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (29)
- [🔍 Indexes](#-indexes) (8)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product ID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Part No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Tool ID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Tool No | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Material_ID | `Date` | 🚫 Not Null | - |
| Material Name | `String` (80) | 🚫 Not Null | - |
| Price | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Customer Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Modified_Date | `Integer` | 🚫 Not Null | - |
| Currency | `String` (2) | 🚫 Not Null | - |
| INCOTERM | `String` (255) | 🚫 Not Null | - |
| Batch Quantity | `Date` | 🚫 Not Null | - |
| PriceQuantity | `Date` | 🚫 Not Null | - |
| DeliveryCost | `Boolean` | 🚫 Not Null | - |
| Comments | `String` | 🚫 Not Null | - |
| Consignment | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| ConsignmentMin | `Date` | 🚫 Not Null | - |
| ConsignmentMax | `Date` | 🚫 Not Null | - |
| CustomerReference | `String` (255) | 🚫 Not Null | - |
| Deconsigned_Stock | `Date` | 🚫 Not Null | - |
| CurrentConsignmentOrder | `String` (255) | 🚫 Not Null | - |
| Con_LastReceived | `Integer` | 🚫 Not Null | - |
| MOQ | `Date` | 🚫 Not Null | - |
| DefaultOrderNumber | `String` (255) | 🚫 Not Null | - |
| MOV | `Boolean` | 🚫 Not Null | - |
| SSLOffsetDays | `Picture` | - | - |
| SSLOverride | `Date` | 🚫 Not Null | - |
| MigrationID | `Date` | - | - |

### Detailed Information

#### Product ID

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Part No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Tool ID

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Tool No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Material_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Material Name

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Price

**Properties:**

- **Type:** Boolean
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Customer Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Modified_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Currency

**Properties:**

- **Type:** String (max length: 2)
- **Constraints:** 🚫 Never Null

---

#### INCOTERM

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Batch Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PriceQuantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DeliveryCost

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Comments

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Consignment

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### ConsignmentMin

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ConsignmentMax

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### CustomerReference

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Deconsigned_Stock

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### CurrentConsignmentOrder

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Con_LastReceived

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### MOQ

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DefaultOrderNumber

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### MOV

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### SSLOffsetDays

**Properties:**

- **Type:** Picture

---

#### SSLOverride

**Properties:**

- **Type:** Date
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
| `Material Name` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Part No` | Keywords | regular | - |
| `Price` | Keywords | regular | - |
| `Product ID` | Keywords | regular | - |
| `Tool No` | Keywords | regular | - |
| `Customer Code` | Keywords | regular | - |
| `Material_ID` | Keywords | regular | - |

### Detailed Information

- **Field:** `Material Name`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Part No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Price`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Product ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Tool No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer Code`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Material_ID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `Product ID` → `Product_ID` | Active |
| `MaterialEntity` | [Material](Material.md) | `Material_ID` → `Unique_ID` | Active |
| `CustomerEntity` | [Customer](Customer.md) | `Customer Code` → `Customer_Code` | Active |
| `ToolsEntity` | [Tools](Tools.md) | `Tool ID` → `Tool_ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `Product ID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `Material_ID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### CustomerEntity

**Links to:** [Customer](Customer.md)

- **Source Field:** `Customer Code`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

#### ToolsEntity

**Links to:** [Tools](Tools.md)

- **Source Field:** `Tool ID`
- **Destination Field:** `Tool_ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `Customer_OrderSelection` | [Customer_Order](Customer_Order.md) | `Product_OptionID` → `ID` | Active |

### Detailed Information

#### Customer_OrderSelection

**Links from:** [Customer_Order](Customer_Order.md)

- **Source Table:** `Customer_Order`
- **Source Field:** `Product_OptionID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:02Z*
