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
- **Generated:** 🕐 2025-11-13T02:47:45Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (26)
- [🔍 Indexes](#-indexes) (11)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (5)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

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

## 🔍 Indexes

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

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | Active | - |
| `Customer_OrderEntity` | [Customer_Order](Customer_Order.md) | `Petes No` → `Petes_No` | Active | - |
| `Advice_NoteEntity` | [Advice_Note](Advice_Note.md) | `Advice_Note_No` → `Advice_Note_No` | Active | - |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `LocationID_l` → `StockLocationID_l` | Active | - |
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `CofCID` → `Cert_Of_Conformance_No` | Active | - |
| `PalletSelection` | [Pallet](Pallet.md) | `CofCID` → `Cert_Of_Conformance_No` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [CofCEntity](../Classes/CofCEntity.md) - Entity class

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:47:45Z*
