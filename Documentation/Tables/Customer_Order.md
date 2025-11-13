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
- **Generated:** 🕐 2025-11-13T02:34:16Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (69)
- [🔍 Indexes](#-indexes) (19)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

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
| Cust Part No | `String` (30) | 🚫 Not Null | - |
| Quantity_Delivered | `Date` | 🚫 Not Null | - |
| Cumulative | `Date` | 🚫 Not Null | - |
| Suggested | `Date` | 🚫 Not Null | - |
| Is_On_hold | `Real` | 🚫 Not Null | - |
| Completed | `Real` | ⚠️ Required, 🚫 Not Null | - |
| Quantity_Required | `Date` | 🚫 Not Null | - |
| 🔑 **Petes_No** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
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

### Detailed Information

#### Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Issue_Date

**Properties:**

- **Type:** Integer
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Date_Received

**Properties:**

- **Type:** Integer
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Code

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Order_No

**Properties:**

- **Type:** String (max length: 18)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Customer_Order_Date

**Properties:**

- **Type:** Integer
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Part_No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Issue_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Quantity_Ordered

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Batch_No

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Customer_Delivery_Date

**Properties:**

- **Type:** Integer
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Our_Delivery_Date

**Properties:**

- **Type:** Integer
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Price_Quantity

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Order_Price

**Properties:**

- **Type:** Boolean
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Is_Replacement

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Tool_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### Nominal_Sale

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Material_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Material_CName

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Tool_ID

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### MaterialOurName

**Properties:**

- **Type:** String (max length: 80)
- **Constraints:** 🚫 Never Null

---

#### Cust Part No

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null, 👁️ Hidden

---

#### Quantity_Delivered

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Cumulative

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Suggested

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Is_On_hold

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Completed

**Properties:**

- **Type:** Real
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Quantity_Required

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### 🔑 Petes_No

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null, 🔒 Not Modifiable

---

#### CalculatedDespatchDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Status

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### Acknowledged

**Properties:**

- **Type:** Real
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Part_Delivery

**Properties:**

- **Type:** Real
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Invoiced

**Properties:**

- **Type:** Real
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Ready_To_Delete

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Is_a_Trial

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Delivered_Value

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Ammeded_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Is_New_Order

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### QtyMonthAfter

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### BoxesMonthAfter

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### OTIF

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### OTIF_Shortfall

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### OTIF_Comments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ConsignmentOTIFCheck

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ProductionReadyDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ReadyOnDate

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DaysLate

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### OrderNotes

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### MCPlanned

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### NSKDelivered

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### NSKUndelivered

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### NSKCurrentSYNStock

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### ConsignmentDummy

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### FinWheelID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### FinWheelMC

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### ConOrderDummy

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Reviewed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DateReviewed

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ReviewedReadyDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Confirmed

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ConfirmedDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ConfirmedDue

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### MakeOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SIMUsageOrder

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Product_OptionID

**Properties:**

- **Type:** Date

---

#### ProcurementProgramOrder

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Forecast

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### FutureYearForecast

**Properties:**

- **Type:** Real

---

## 🔍 Indexes

### Quick Reference

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

### Detailed Information

- **Field:** `Petes_No` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Reviewed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Forecast`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Product_ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Completed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Our_Delivery_Date`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Confirmed`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Part_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProcurementProgramOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer_Delivery_Date`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Material_ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `FinWheelID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Product_OptionID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer_Order_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `FutureYearForecast`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Ready_To_Delete`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MakeOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Customer_Code`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Ammeded_Date`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `Product_ID` → `Product_ID` | Active |
| `MaterialEntity` | [Material](Material.md) | `Material_ID` → `Unique_ID` | Active |
| `CustomerEntity` | [Customer](Customer.md) | `Customer_Code` → `Customer_Code` | Active |
| `Product_OptionEntity` | [Product_Option](Product_Option.md) | `Product_OptionID` → `ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `Product_ID`
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

- **Source Field:** `Customer_Code`
- **Destination Field:** `Customer_Code`
- **State:** Active

---

#### Product_OptionEntity

**Links to:** [Product_Option](Product_Option.md)

- **Source Field:** `Product_OptionID`
- **Destination Field:** `ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `CofCSelection` | [CofC](CofC.md) | `Petes No` → `Petes_No` | Active |
| `OrderPickRequestSelection` | [OrderPickRequest](OrderPickRequest.md) | `CustomerOrderID` → `Petes_No` | Active |

### Detailed Information

#### CofCSelection

**Links from:** [CofC](CofC.md)

- **Source Table:** `CofC`
- **Source Field:** `Petes No`
- **This Table Field:** `Petes_No`
- **State:** Active

---

#### OrderPickRequestSelection

**Links from:** [OrderPickRequest](OrderPickRequest.md)

- **Source Table:** `OrderPickRequest`
- **Source Field:** `CustomerOrderID`
- **This Table Field:** `Petes_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:16Z*
