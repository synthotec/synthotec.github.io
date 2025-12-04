---
layout : default
title : Finished_Stock
parent : Tables
---
# Finished_Stock

📊 **Overview:** 12 Fields | 6 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 12
- **UUID:** 51AABC1ABE247B49864812D98CE6E30B
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-03T16:23:27Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Forms](#-forms) (9)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| FinishedStockID | `Long Integer` | ⚠️ Required, 🚫 Not Null | - |
| ProductID_l | `Long Integer` | ⚠️ Required, 🚫 Not Null | - |
| Reuse_Issue_No | `String` (5) | 🚫 Not Null | - |
| MaterialID | `Integer` | 🚫 Not Null | - |
| Stock_Quantity | `Long Integer` | 🚫 Not Null | - |
| Reuse_NoOfBoxes | `Long Integer` | 🚫 Not Null | - |
| Reuse_PartBoxQty | `Long Integer` | 🚫 Not Null | - |
| Reuse_WIP | `Long Integer` | 🚫 Not Null | - |
| LocationID_l | `Long Integer` | 🚫 Not Null | - |
| Works_Order_No | `Long Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Pallet_ID | `Long Integer` | 🚫 Not Null | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `LocationID_l` | Keywords | regular | - |
| `ProductID_l` | Keywords | regular | - |
| `Works_Order_No` | Keywords | regular | - |
| `FinishedStockID` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | Active | - |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `LocationID_l` → `StockLocationID_l` | Active | - |

## 🔗 Related Items

### 📄 Forms

- [%2AStockControl](../Forms/%2AStockControl.md) - Data source for %2AStockControl form
- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [ProductStockTake](../Forms/ProductStockTake.md) - Data source for ProductStockTake form
- [QuarantineManager](../Forms/QuarantineManager.md) - Data source for QuarantineManager form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-03T16:23:27Z*
