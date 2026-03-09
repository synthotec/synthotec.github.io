---
layout : default
title : ProductPackaging
parent : Classes
---
# ProductPackaging [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/ProductPackaging.4dm)

📊 **Overview:** 3 Functions

## 📝 Description

DataClass for product packaging records, managing which packaging supplies are required per product. Provides on-demand generation of customer-specific packaging records triggered by a global settings flag.

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:30.855Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
    - [queueCustomerPackagingUpdate](#queuecustomerpackagingupdate)
    - [generateCustomerPackaging](#generatecustomerpackaging)
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns migration configuration disabling entity linking for ProductPackaging

**Returns:** `Object`

---

#### queueCustomerPackagingUpdate {#queuecustomerpackagingupdate}


```4d
Function queueCustomerPackagingUpdate
```

Queues customer packaging for regeneration by setting global flag

---

#### generateCustomerPackaging {#generatecustomerpackaging}


```4d
Function generateCustomerPackaging
```

Generates customer-specific packaging records for each product-customer combination if flag is set

---

## Related Items {#related-items}

### 🗂️ Tables

- [ProductPackaging](../Tables/ProductPackaging.md) - ORDA DataClass class for ProductPackaging table

### � Related Classes

- [ProductPackagingEntity](ProductPackagingEntity.md) - ORDA Entity class for ProductPackaging table

### � Forms

- [PackagingOptions](../Forms/PackagingOptions.md) - Data source for PackagingOptions form
- [TransferSupply](../Forms/TransferSupply.md) - Data source for TransferSupply form

---

*Generated from ProductPackaging.4dm*
