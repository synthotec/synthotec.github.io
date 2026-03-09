---
layout : default
title : CofCEntity
parent : Classes
---
# CofCEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CofCEntity.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

Entity representing a Certificate of Conformance (delivery certificate) linking a customer order, works order, and stock movement. Provides cancellation support that reverses stock movements and reduces customer order delivered quantities.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.170Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [cancel](#cancel) → `$Cancelled : Boolean`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### cancel {#cancel}


```4d
Function cancel -> $Cancelled : Boolean
```

Cancels the Certificate of Conformance by reversing stock movements and reducing customer order delivered quantity

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [CofC](../Tables/CofC.md) - ORDA Entity class for CofC table

### � Forms

- [CancelAdviceNote](../Forms/CancelAdviceNote.md) - Data source for CancelAdviceNote form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [SNRSUMMARY](../Forms/SNRSUMMARY.md) - Data source for SNRSUMMARY form
- [StockMovements](../Forms/StockMovements.md) - Data source for StockMovements form

---

*Generated from CofCEntity.4dm*
