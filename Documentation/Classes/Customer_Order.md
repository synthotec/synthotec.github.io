# Customer_Order

**Extends:** `DataClass`

## Table of Contents

### Functions

- [classicMakeOrderSort()](#classicmakeordersort)
- [classicOrderOverviewSort()](#classicorderoverviewsort)

---

## Functions

### classicMakeOrderSort {#classicmakeordersort}
 `[local]`

```4d
Function classicMakeOrderSort($ProductEntity : cs.ProductEntity)
```

ORDER BY([Customer_Order]; [Customer_Order]Forecast; >; *)

---

### classicOrderOverviewSort {#classicorderoverviewsort}
 `[local]`

```4d
Function classicOrderOverviewSort($ProductEntity : cs.ProductEntity)
```

ORDER BY([Customer_Order]; [Customer_Order]Completed; >; [Customer_Order]Forecast; <; *)

---

---

*Generated from Customer_Order.4dm*
*Last updated: 2025-11-12T17:17:31.437Z*
