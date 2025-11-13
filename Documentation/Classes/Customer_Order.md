---
layout : default
title : Customer_Order
parent : Classes
---
# Customer_Order

📊 **Overview:** 2 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2025-11-13T12:58:33.575Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**⚙️ Functions (2):**

- [classicMakeOrderSort](#classicmakeordersort) (1 param) 🖥️
- [classicOrderOverviewSort](#classicorderoverviewsort) (1 param) 🖥️

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

### 📦 Related Classes

- [Customer_Order](Customer_Order.md) - DataClass class
- [Customer_OrderEntity](Customer_OrderEntity.md) - Entity class

### 🗂️ Used By Tables

- [Customer_Order](../Tables/Customer_Order.md) - DataClass class

---

*Generated from Customer_Order.4dm*
