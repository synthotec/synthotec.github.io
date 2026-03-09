---
layout : default
title : OrderPickRequestSelection
parent : Classes
---
# OrderPickRequestSelection [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/OrderPickRequestSelection.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

Entity selection of order pick request lines, providing an aggregate helper to sum the total unprocessed quantity across all lines whose parent pick request has not yet been processed.

**Extends:** `EntitySelection`

🕐 *Last updated: 2026-03-09T14:45:30.134Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getUnprocessedQuantity](#getunprocessedquantity) → `Integer` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getUnprocessedQuantity {#getunprocessedquantity}
 `[🖥️ local]`

```4d
Function getUnprocessedQuantity -> Integer
```

Returns total quantity from all unprocessed pick requests in this selection

**Returns:** `Integer`

---

## Related Items {#related-items}

### 🗂️ Tables

- [OrderPickRequest](../Tables/OrderPickRequest.md) - ORDA EntitySelection class for OrderPickRequest table

### � Related Classes

- [OrderPickRequestEntity](OrderPickRequestEntity.md) - ORDA Entity class for OrderPickRequest table

### � Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form

---

*Generated from OrderPickRequestSelection.4dm*
