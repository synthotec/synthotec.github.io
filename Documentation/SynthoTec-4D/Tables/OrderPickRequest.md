---
layout : default
title : OrderPickRequest
parent : Tables
---
# OrderPickRequest

📊 **Overview:** 4 Fields | 3 Indexes | 2 Many-to-One Relations | 2 One-to-Many Relations

## 📝 Description

🗨️ Transaction table linking customer orders to warehouse pick requests. Generates picking tasks for order fulfillment workflow.

## ℹ️ Table Information

- **Table ID:** 124
- **UUID:** 2BE22D1782098249A524034DE15E0047
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-12-04T14:35:24Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)
- [🔗 Related Items](#-related-items)
  - [Classes](#-classes) (2)
  - [Forms](#-forms) (1)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Long Integer` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PickRequestID | `Long Integer` | - | - |
| CustomerOrderID | `Long Integer` | - | - |
| Quantity | `Long Integer` | - | - |

## 🔍 Indexes

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `CustomerOrderID` | Keywords | regular | - |
| `PickRequestID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

## 🔗 Many-to-One Relations

| Relation Name | Destination Table | Source → Destination | State | Description |
|:--------------|:------------------|:---------------------|:------|:------------|
| `PickRequestEntity` | [PickRequest](PickRequest.md) | `PickRequestID` → `ID` | Active | - |
| `Customer_OrderEntity` | [Customer_Order](Customer_Order.md) | `CustomerOrderID` → `Petes_No` | Active | - |

## 🔗 One-to-Many Relations

| Relation Name | Source Table | Source → Destination | State | Description |
|:--------------|:-------------|:---------------------|:------|:------------|
| `PalletSelection` | [Pallet](Pallet.md) | `OrderPickRequestID` → `ID` | Active | - |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `OrderPickRequestID` → `ID` | Active | - |

## 🔗 Related Items

### 📦 Classes

- [OrderPickRequestEntity](../Classes/OrderPickRequestEntity.md) - ORDA Entity class for OrderPickRequest table
- [OrderPickRequestSelection](../Classes/OrderPickRequestSelection.md) - ORDA EntitySelection class for OrderPickRequest table

### 📄 Forms

- [%2AOrderPicking](../Forms/%2AOrderPicking.md) - Data source for %2AOrderPicking form

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-12-04T14:35:24Z*
