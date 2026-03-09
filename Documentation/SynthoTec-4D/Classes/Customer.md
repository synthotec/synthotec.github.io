---
layout : default
title : Customer
parent : Classes
---
# Customer [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Customer.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for customer account records, managing customer codes, addresses, contacts, and order history. Supports entity migration with linking enabled, allowing records to be matched and synced from a remote datastore.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:29.192Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns configuration for entity migration including linking settings and custom property formulas for Customer_Code

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Customer](../Tables/Customer.md) - ORDA DataClass class for Customer table

### � Related Classes

- [CustomerEntity](CustomerEntity.md) - ORDA Entity class for Customer table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [BOM_CustomerTransport](../Forms/BOM_CustomerTransport.md) - Data source for BOM_CustomerTransport form
- [ConfirmOrderDates](../Forms/ConfirmOrderDates.md) - Data source for ConfirmOrderDates form
- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form
- [Manufacture](../Forms/Manufacture.md) - Data source for Manufacture form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [PackingListGenerator](../Forms/PackingListGenerator.md) - Data source for PackingListGenerator form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form

---

*Generated from Customer.4dm*
