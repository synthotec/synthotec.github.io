---
layout : default
title : Customer_Order
parent : Classes
---
# Customer_Order [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer_Order.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-19T18:10:05.537Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [classicMakeOrderSort](#classicmakeordersort) (1 param) 🖥️
    - [classicOrderOverviewSort](#classicorderoverviewsort) (1 param) 🖥️
- [🔗 Related Items](#related-items)

---

## Functions {#functions}

### Regular Functions

#### classicMakeOrderSort {#classicmakeordersort}
 `[🖥️ local]`

```4d
Function classicMakeOrderSort($ProductEntity : cs.ProductEntity)
```

ORDER BY([Customer_Order]; [Customer_Order]Forecast; >; *)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductEntity` | `cs.ProductEntity` | - | - |

---

#### classicOrderOverviewSort {#classicorderoverviewsort}
 `[🖥️ local]`

```4d
Function classicOrderOverviewSort($ProductEntity : cs.ProductEntity)
```

ORDER BY([Customer_Order]; [Customer_Order]Completed; >; [Customer_Order]Forecast; <; *)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ProductEntity` | `cs.ProductEntity` | - | - |

---

## Related Items {#related-items}

### 🗂️ Tables

- [Customer_Order](../Tables/Customer_Order.md) - ORDA DataClass class for Customer_Order table

### � Related Classes

- [Customer_OrderEntity](Customer_OrderEntity.md) - ORDA Entity class for Customer_Order table

### � Forms

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

*Generated from Customer_Order.4dm*
