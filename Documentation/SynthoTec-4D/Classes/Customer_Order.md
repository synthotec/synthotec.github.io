---
layout : default
title : Customer_Order
parent : Classes
---
# Customer_Order [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer_Order.4dm)

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-14T16:53:00.180Z*

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

- [Customer_Order](../Tables/Customer_Order.md) - Source table for this ORDA class

### � Related Classes

- [Customer_OrderEntity](Customer_OrderEntity.md) - ORDA Entity class for Customer_Order table

---

*Generated from Customer_Order.4dm*
