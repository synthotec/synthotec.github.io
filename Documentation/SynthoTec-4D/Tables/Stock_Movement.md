---
layout : default
title : Stock_Movement
parent : Tables
---
# Stock_Movement

📊 **Overview:** 24 Fields | 4 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 5
- **UUID:** F1AE2CED84FC204E9E788B8FF9BE9359
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:21Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (24)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (4)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Movement_Type_From_s | `String` (2) | 🚫 Not Null | - |
| Date_Of_Movement_d | `Date` | 🚫 Not Null | - |
| Works_Order_No_l | `Long Integer` | 🚫 Not Null | - |
| Quantity_In_l | `Long Integer` | 🚫 Not Null | - |
| Advice_Note_No_i | `Long Integer` | 🚫 Not Null | - |
| Quantity_Out_l | `Long Integer` | 🚫 Not Null | - |
| Stock_Movement_b | `Boolean` | 🚫 Not Null | - |
| Cert_Of_Conformance_No_i | `Long Integer` | 🚫 Not Null | - |
| From_Location_l | `Long Integer` | 🚫 Not Null | - |
| UserName_txt | `String` | 🚫 Not Null | - |
| ProductID_l | `Long Integer` | 🚫 Not Null | - |
| To_Location_l | `Long Integer` | 🚫 Not Null | - |
| Reason_For_Movement_txt | `String` | 🚫 Not Null | - |
| Movement_Type_To_s | `String` (2) | 🚫 Not Null | - |
| StockMovementID_l | `Long Integer` | 🚫 Not Null | - |
| DeliveryMethod_txt | `String` | 🚫 Not Null | - |
| Order_No_s | `String` (30) | 🚫 Not Null | - |
| FullPallet_l | `Long Integer` | 🚫 Not Null | - |
| is_consigment_stock_b | `Boolean` | 🚫 Not Null | - |
| NSKFromBox | `Long Integer` | 🚫 Not Null | - |
| NSKToBox | `Long Integer` | 🚫 Not Null | - |
| TransactionID | `Long Integer` | 🚫 Not Null | - |
| MoveListNum | `Long Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ProductID_l` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Works_Order_No_l` | Keywords | regular | - |
| `Date_Of_Movement_d` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No_l` → `Works_Order_No` | Active | - |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `To_Location_l` → `StockLocationID_l` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [EDIgenerator](../Forms/EDIgenerator.md) - Data source for EDIgenerator form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form
- [StockMovements](../Forms/StockMovements.md) - Data source for StockMovements form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:21Z*
