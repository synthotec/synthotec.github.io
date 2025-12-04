---
layout : default
title : Customer_Order
parent : Tables
---
# Customer_Order

📊 **Overview:** 69 Fields | 19 Indexes | 4 Many-to-One Relations | 2 One-to-Many Relations

## 📝 Description

🗨️ Transaction table for customer purchase orders. Stores order details, delivery schedules, pricing, and status. Links to Customers, Products, and generates WorksOrders for production.

## ℹ️ Table Information

- **Table ID:** 3
- **UUID:** BEB2206FADBF794D8690FF16FF7721B1
- **Primary Key:** 🔑 `Petes_No`
- **Generated:** 🕐 2025-12-04T14:33:31Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (69)
- [🔍 Indexes](#-indexes) (19)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (18)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product_ID | `Long Integer` | 🚫 Not Null | - |
| Issue_Date | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Date_Received | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Customer_Code | `String` (3) | ⚠️ Required, 🚫 Not Null | - |
| Customer_Order_No | `String` (18) | ⚠️ Required, 🚫 Not Null | - |
| Customer_Order_Date | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Part_No | `String` (30) | ⚠️ Required, 🚫 Not Null | - |
| Issue_No | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Quantity_Ordered | `Long Integer` | ⚠️ Required, 🚫 Not Null | - |
| Batch_No | `String` | 🚫 Not Null | - |
| Customer_Delivery_Date | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Our_Delivery_Date | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Price_Quantity | `Integer` | 🚫 Not Null | - |
| Order_Price | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Is_Replacement | `Boolean` | 🚫 Not Null | - |
| Tool_No | `String` (5) | 🚫 Not Null | - |
| Nominal_Sale | `Real` | 🚫 Not Null | - |
| Material_ID | `Long Integer` | 🚫 Not Null | - |
| Material_CName | `String` (80) | 🚫 Not Null | - |
| Tool_ID | `Integer` | 🚫 Not Null | - |
| MaterialOurName | `String` (80) | 🚫 Not Null | - |
| Cust Part No | `String` (30) | 🚫 Not Null, ���️ Hidden | - |
| Quantity_Delivered | `Long Integer` | 🚫 Not Null | - |
| Cumulative | `Long Integer` | 🚫 Not Null | - |
| Suggested | `Long Integer` | 🚫 Not Null | - |
| Is_On_hold | `Boolean` | 🚫 Not Null | - |
| Completed | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Quantity_Required | `Long Integer` | 🚫 Not Null | - |
| 🔑 **Petes_No** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null, ��� Not Modifiable | - |
| CalculatedDespatchDate | `Date` | 🚫 Not Null | - |
| Status | `String` (3) | 🚫 Not Null | - |
| Acknowledged | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Part_Delivery | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Invoiced | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Ready_To_Delete | `Boolean` | 🚫 Not Null | - |
| Is_a_Trial | `Boolean` | 🚫 Not Null | - |
| Delivered_Value | `Real` | 🚫 Not Null | - |
| Ammeded_Date | `Date` | 🚫 Not Null | - |
| Is_New_Order | `Boolean` | 🚫 Not Null | - |
| QtyMonthAfter | `Long Integer` | 🚫 Not Null | - |
| BoxesMonthAfter | `Integer` | 🚫 Not Null | - |
| OTIF | `Boolean` | 🚫 Not Null | - |
| OTIF_Shortfall | `Long Integer` | 🚫 Not Null | - |
| OTIF_Comments | `String` (255) | 🚫 Not Null | - |
| ConsignmentOTIFCheck | `Boolean` | 🚫 Not Null | - |
| ProductionReadyDate | `Date` | 🚫 Not Null | - |
| ReadyOnDate | `Long Integer` | 🚫 Not Null | - |
| DaysLate | `Integer` | 🚫 Not Null | - |
| OrderNotes | `String` | 🚫 Not Null | - |
| MCPlanned | `Integer` | 🚫 Not Null | - |
| NSKDelivered | `Integer` | 🚫 Not Null | - |
| NSKUndelivered | `Integer` | 🚫 Not Null | - |
| NSKCurrentSYNStock | `Integer` | 🚫 Not Null | - |
| ConsignmentDummy | `Boolean` | 🚫 Not Null | - |
| FinWheelID | `Long Integer` | 🚫 Not Null | - |
| FinWheelMC | `Integer` | 🚫 Not Null | - |
| ConOrderDummy | `Boolean` | 🚫 Not Null | - |
| Reviewed | `Boolean` | 🚫 Not Null | - |
| DateReviewed | `Date` | 🚫 Not Null | - |
| ReviewedReadyDate | `Date` | 🚫 Not Null | - |
| Confirmed | `Boolean` | 🚫 Not Null | - |
| ConfirmedDate | `Date` | 🚫 Not Null | - |
| ConfirmedDue | `Date` | 🚫 Not Null | - |
| MakeOrder | `Long Integer` | 🚫 Not Null | - |
| SIMUsageOrder | `Boolean` | 🚫 Not Null | - |
| Product_OptionID | `Long Integer` | - | - |
| ProcurementProgramOrder | `Boolean` | 🚫 Not Null | - |
| Forecast | `Boolean` | 🚫 Not Null | - |
| FutureYearForecast | `Boolean` | - | - |

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

### 📄 Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [ConfirmOrderDates](../Forms/ConfirmOrderDates.md) - Data source for ConfirmOrderDates form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [PackingListGenerator](../Forms/PackingListGenerator.md) - Data source for PackingListGenerator form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form
- [PriceChangeOrders](../Forms/PriceChangeOrders.md) - Data source for PriceChangeOrders form
- [Scheduler](../Forms/Scheduler.md) - Data source for Scheduler form
- [Schedule_Variables](../Forms/Schedule_Variables.md) - Data source for Schedule_Variables form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:33:31Z*
