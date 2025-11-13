---
layout : default
title : CofC
parent : Tables
---
# CofC

📊 **Overview:** 26 Fields | 11 Indexes | 5 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 6
- **UUID:** 81B9B2AF685A1B4E892794C866475FCC
- **Primary Key:** 🔑 `Cert_Of_Conformance_No`
- **Generated:** 🕐 2025-11-13T02:34:19Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (26)
- [🔍 Indexes](#-indexes) (11)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (5)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **Cert_Of_Conformance_No** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, ⚠️ Required, 🚫 Not Null | Test |
| Customer_Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Created_Date | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Advice_Note_No | `Date` | 🚫 Not Null | - |
| Part No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Customer_Order_No | `String` (20) | ⚠️ Required, 🚫 Not Null | - |
| MovementCofC | `Real` | 🚫 Not Null | - |
| RMC_Nos | `String` (30) | 🚫 Not Null | - |
| Delivery_Quantity | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Works_Order_No | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Petes No | `Date` | 🚫 Not Null | - |
| Quantity_Loose | `Date` | 🚫 Not Null | - |
| Price | `Boolean` | 🚫 Not Null | - |
| Nunber_Of_Boxes | `Picture` | 🚫 Not Null | - |
| Number_In_Box | `Date` | 🚫 Not Null | - |
| loose | `String` | 🚫 Not Null | - |
| Order_Completed | `Real` | 🚫 Not Null | - |
| Batch_No | `String` (5) | 🚫 Not Null | - |
| CofC_Report | `Real` | 🚫 Not Null | - |
| Invoice_Report | `Real` | 🚫 Not Null | - |
| ProductID_l | `Date` | 🚫 Not Null | - |
| Date_Int | `Date` | 🚫 Not Null | - |
| DeliveredDate_d | `Integer` | 🚫 Not Null | - |
| LocationID_l | `Date` | 🚫 Not Null | - |
| LocationName_s | `String` (30) | 🚫 Not Null | - |
| Delivery_Method_s | `String` (30) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 Cert_Of_Conformance_No

🗨️ Test

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Created_Date

**Properties:**

- **Type:** Integer
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Advice_Note_No

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Part No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Order_No

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### MovementCofC

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RMC_Nos

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Delivery_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Works_Order_No

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Petes No

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Quantity_Loose

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Price

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Nunber_Of_Boxes

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Number_In_Box

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### loose

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Order_Completed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Batch_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### CofC_Report

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Invoice_Report

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Date_Int

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DeliveredDate_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### LocationID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### LocationName_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Delivery_Method_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Cert_Of_Conformance_No` | Keywords | regular | ✨ Yes |
| `CofC_Report` | Keywords | regular | - |
| `Works_Order_No` | Keywords | regular | - |
| `Advice_Note_No` | Keywords | regular | - |
| `Date_Int` | Keywords | regular | - |
| `Customer_Code` | Keywords | regular | - |
| `Invoice_Report` | Keywords | regular | - |
| `ProductID_l` | Keywords | regular | - |
| `MovementCofC` | Keywords | regular | - |
| `Part No` | Keywords | regular | - |
| `Petes No` | Keywords | regular | - |

### Detailed Information

- **Field:** `Cert_Of_Conformance_No` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `CofC_Report`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Works_Order_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Advice_Note_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Date_Int`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer_Code`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Invoice_Report`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MovementCofC`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Part No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Petes No`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | Active |
| `Customer_OrderEntity` | [Customer_Order](Customer_Order.md) | `Petes No` → `Petes_No` | Active |
| `Advice_NoteEntity` | [Advice_Note](Advice_Note.md) | `Advice_Note_No` → `Advice_Note_No` | Active |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `LocationID_l` → `StockLocationID_l` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### Customer_OrderEntity

**Links to:** [Customer_Order](Customer_Order.md)

- **Source Field:** `Petes No`
- **Destination Field:** `Petes_No`
- **State:** Active

---

#### Advice_NoteEntity

**Links to:** [Advice_Note](Advice_Note.md)

- **Source Field:** `Advice_Note_No`
- **Destination Field:** `Advice_Note_No`
- **State:** Active

---

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `LocationID_l`
- **Destination Field:** `StockLocationID_l`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `CofCID` → `Cert_Of_Conformance_No` | Active |
| `PalletSelection` | [Pallet](Pallet.md) | `CofCID` → `Cert_Of_Conformance_No` | Active |

### Detailed Information

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** Active

---

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `CofCID`
- **This Table Field:** `Cert_Of_Conformance_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:19Z*
