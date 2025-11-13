---
layout : default
title : Customer_Order
parent : Classes
---
# Customer_Order

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T23:17:37.912Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Regular Functions (2):**

- [classicMakeOrderSort](#classicmakeordersort) (1 param) 🖥️
- [classicOrderOverviewSort](#classicorderoverviewsort) (1 param) 🖥️

### 🔗 Related Items

- [Tables](#️-tables) (2)
- [Classes](#-related-classes) (2)

---

## ⚙️ Functions

### ⚙️ Regular Functions

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

## 🔗 Related Items

### 🗂️ Tables

- [Customer_Order](../Tables/Customer_Order.md) - Source table for this ORDA class

### � Related Classes

- [Customer_OrderEntity](Customer_OrderEntity.md) - ORDA Entity class for Customer_Order table

---

*Generated from Customer_Order.4dm*
