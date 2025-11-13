---
layout : default
title : Customer_Order
parent : Tables
---
# Customer_Order

📊 **Overview:** 69 Fields | 19 Indexes | 4 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 3
- **UUID:** BEB2206FADBF794D8690FF16FF7721B1
- **Primary Key:** 🔑 `Petes_No`
- **Generated:** 🕐 2025-11-13T16:07:54Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (69)
- [🔍 Indexes](#-indexes) (19)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product_ID | `Date` | 🚫 Not Null | - |
| Issue_Date | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Date_Received | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Customer_Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Customer_Order_No | `String` (18) | ⚠️ Required, 🚫 Not Null | - |
| Customer_Order_Date | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Part_No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Issue_No | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Quantity_Ordered | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Batch_No | `String` | 🚫 Not Null | - |
| Customer_Delivery_Date | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Our_Delivery_Date | `Integer` | ⚠️ Required, 🚫 Not Null | - |
| Price_Quantity | `Picture` | 🚫 Not Null | - |
| Order_Price | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Is_Replacement | `Real` | 🚫 Not Null | - |
| Tool_No | `String` (5) | 🚫 Not Null | - |
| Nominal_Sale | `Boolean` | 🚫 Not Null | - |
| Material_ID | `Date` | 🚫 Not Null | - |
| Material_CName | `String` (80) | 🚫 Not Null | - |
| Tool_ID | `Picture` | 🚫 Not Null | - |
| MaterialOurName | `String` (80) | 🚫 Not Null | - |
| Cust Part No | `String` (30) | 🚫 Not Null, ���️ Hidden | - |
| Quantity_Delivered | `Date` | 🚫 Not Null | - |
| Cumulative | `Date` | 🚫 Not Null | - |
| Suggested | `Date` | 🚫 Not Null | - |
| Is_On_hold | `Real` | 🚫 Not Null | - |
| Completed | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Quantity_Required | `Date` | 🚫 Not Null | - |
| 🔑 **Petes_No** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null, ��� Not Modifiable | - |
| CalculatedDespatchDate | `Integer` | 🚫 Not Null | - |
| Status | `String` (3) | 🚫 Not Null | - |
| Acknowledged | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Part_Delivery | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Invoiced | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Ready_To_Delete | `Real` | 🚫 Not Null | - |
| Is_a_Trial | `Real` | 🚫 Not Null | - |
| Delivered_Value | `Boolean` | 🚫 Not Null | - |
| Ammeded_Date | `Integer` | 🚫 Not Null | - |
| Is_New_Order | `Real` | 🚫 Not Null | - |
| QtyMonthAfter | `Date` | 🚫 Not Null | - |
| BoxesMonthAfter | `Picture` | 🚫 Not Null | - |
| OTIF | `Real` | 🚫 Not Null | - |
| OTIF_Shortfall | `Date` | 🚫 Not Null | - |
| OTIF_Comments | `String` (255) | 🚫 Not Null | - |
| ConsignmentOTIFCheck | `Real` | 🚫 Not Null | - |
| ProductionReadyDate | `Integer` | 🚫 Not Null | - |
| ReadyOnDate | `Date` | 🚫 Not Null | - |
| DaysLate | `Picture` | 🚫 Not Null | - |
| OrderNotes | `String` | 🚫 Not Null | - |
| MCPlanned | `Picture` | 🚫 Not Null | - |
| NSKDelivered | `Undefined` | 🚫 Not Null | - |
| NSKUndelivered | `Undefined` | 🚫 Not Null | - |
| NSKCurrentSYNStock | `Undefined` | 🚫 Not Null | - |
| ConsignmentDummy | `Real` | 🚫 Not Null | - |
| FinWheelID | `Date` | 🚫 Not Null | - |
| FinWheelMC | `Picture` | 🚫 Not Null | - |
| ConOrderDummy | `Real` | 🚫 Not Null | - |
| Reviewed | `Real` | 🚫 Not Null | - |
| DateReviewed | `Integer` | 🚫 Not Null | - |
| ReviewedReadyDate | `Integer` | 🚫 Not Null | - |
| Confirmed | `Real` | 🚫 Not Null | - |
| ConfirmedDate | `Integer` | 🚫 Not Null | - |
| ConfirmedDue | `Integer` | 🚫 Not Null | - |
| MakeOrder | `Date` | 🚫 Not Null | - |
| SIMUsageOrder | `Real` | 🚫 Not Null | - |
| Product_OptionID | `Date` | - | - |
| ProcurementProgramOrder | `Real` | 🚫 Not Null | - |
| Forecast | `Real` | 🚫 Not Null | - |
| FutureYearForecast | `Real` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Petes_No` | Keywords | regular | ✨ Yes |
| `Reviewed` | Keywords | regular | - |
| `Forecast` | Keywords | regular | - |
| `Product_ID` | Keywords | regular | - |
| `Completed` | Keywords | regular | - |
| `Our_Delivery_Date` | Keywords | regular | - |
| `Confirmed` | Keywords | regular | - |
| `Part_No` | Keywords | regular | - |
| `ProcurementProgramOrder` | Keywords | regular | - |
| `Customer_Delivery_Date` | Keywords | regular | - |
| `Material_ID` | Keywords | regular | - |
| `FinWheelID` | Keywords | regular | - |
| `Product_OptionID` | Keywords | regular | - |
| `Customer_Order_No` | Keywords | regular | - |
| `FutureYearForecast` | Keywords | regular | - |
| `Ready_To_Delete` | Keywords | regular | - |
| `MakeOrder` | Keywords | regular | - |
| `Customer_Code` | Keywords | regular | - |
| `Ammeded_Date` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `ProductEntity` | [Product](Product.md) | `Product_ID` → `Product_ID` | Active | - |
| `MaterialEntity` | [Material](Material.md) | `Material_ID` → `Unique_ID` | Active | - |
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | Active | - |
| `Product_OptionEntity` | [Product_Option](Product_Option.md) | `Product_OptionID` → `ID` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `CofCSelection` | [CofC](CofC.md) | `Petes No` → `Petes_No` | Active | - |
| `OrderPickRequestSelection` | [OrderPickRequest](OrderPickRequest.md) | `CustomerOrderID` → `Petes_No` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [Customer_Order](../Classes/Customer_Order.md) - ORDA DataClass class for Customer_Order table
- [Customer_OrderEntity](../Classes/Customer_OrderEntity.md) - ORDA Entity class for Customer_Order table

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T16:07:54Z*
