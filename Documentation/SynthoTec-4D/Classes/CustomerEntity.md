---
layout : default
title : CustomerEntity
parent : Classes
---
# CustomerEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CustomerEntity.4dm)

📊 **Overview:** 2 Functions | 1 Getters

## 📝 Description

Entity representing a customer account with full postal address, contact details, invoice dates, label settings, acknowledgement flags, and cumulative order totals. Supports 50+ field migration rules for syncing from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:29.213Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [HasMigrationID](#hasmigrationid) 🔍 → `Boolean`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.CustomerEntity) -> $Collection : Collection
```

Defines migration rules for syncing customer entity data from a remote source (50+ properties)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.CustomerEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.CustomerEntity)
```

Synchronizes related entity selections (WorksOrder, Product_Option, PickRequest, Customer_Order, Approvals) during migration

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.CustomerEntity` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### HasMigrationID {#hasmigrationid}
 `[🔍 get only, 🖥️ local]`

```4d
Function get HasMigrationID -> Boolean
```

Returns true if this entity has a valid migration ID (not null and not empty string)

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Customer](../Tables/Customer.md) - ORDA Entity class for Customer table

### � Related Classes

- [Customer](Customer.md) - ORDA DataClass class for Customer table

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

*Generated from CustomerEntity.4dm*
