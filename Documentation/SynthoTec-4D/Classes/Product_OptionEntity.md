---
layout : default
title : Product_OptionEntity
parent : Classes
---
# Product_OptionEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Product_OptionEntity.4dm)

📊 **Overview:** 3 Functions | 1 Getters

## 📝 Description

Entity representing a product option record, storing part number, tool number, material name, price, and consignment flag for a specific product-customer-tool combination. Supports migration sync from a remote datastore.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:30.882Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationRules](#getmigrationrules) (1 param) → `$Collection : Collection` 🖥️
    - [syncMigrationSelections](#syncmigrationselections) (1 param) 🖥️
    - [createCustomer_OrderEntity](#createcustomer_orderentity) (4 params) → `$Customer_OrderEntity : cs.Customer_OrderEntity` 🖥️
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [UnitPrice](#unitprice) 🔍 → `Real`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationRules {#getmigrationrules}
 `[🖥️ local]`

```4d
Function getMigrationRules($RemoteEntity : cs.Product_OptionEntity) -> $Collection : Collection
```

Returns collection of entity migration rules defining which fields to overwrite/fill and related entities to sync

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.Product_OptionEntity` | - | - |

**Returns:** `Collection`

---

#### syncMigrationSelections {#syncmigrationselections}
 `[🖥️ local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.Product_OptionEntity)
```

Synchronizes related entity selections during migration (currently commented out/not implemented)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RemoteEntity` | `cs.Product_OptionEntity` | - | - |

---

#### createCustomer_OrderEntity {#createcustomer_orderentity}
 `[🖥️ local]`

```4d
Function createCustomer_OrderEntity($Quantity : Integer; $CustomerDueDate : Date; $OrderNumber : Text; $BatchNumber : Text) -> $Customer_OrderEntity : cs.Customer_OrderEntity
```

Creates and returns a pre-filled Customer_OrderEntity initialized with fields from this Product_OptionEntity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Quantity` | `Integer` | - | - |
| `$CustomerDueDate` | `Date` | - | - |
| `$OrderNumber` | `Text` | - | - |
| `$BatchNumber` | `Text` | - | - |

**Returns:** `cs.Customer_OrderEntity`

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### UnitPrice {#unitprice}
 `[🔍 get only]`

```4d
Function get UnitPrice -> Real
```

Returns the unit price as Price divided by PriceQuantity (defaults to 100 if PriceQuantity is zero)

**Returns:** `Real`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Product_Option](../Tables/Product_Option.md) - ORDA Entity class for Product_Option table

### � Related Classes

- [Product_Option](Product_Option.md) - ORDA DataClass class for Product_Option table

### � Forms

- [BOM](../Forms/BOM.md) - Data source for BOM form
- [ConsignmentEntry](../Forms/ConsignmentEntry.md) - Data source for ConsignmentEntry form
- [ConsignmentSSLs](../Forms/ConsignmentSSLs.md) - Data source for ConsignmentSSLs form
- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form
- [CustomerOrderEntry](../Forms/CustomerOrderEntry.md) - Data source for CustomerOrderEntry form
- [Forecast](../Forms/Forecast.md) - Data source for Forecast form
- [OrderOverview](../Forms/OrderOverview.md) - Data source for OrderOverview form
- [Pricing](../Forms/Pricing.md) - Data source for Pricing form
- [SIMImporter](../Forms/SIMImporter.md) - Data source for SIMImporter form

---

*Generated from Product_OptionEntity.4dm*
