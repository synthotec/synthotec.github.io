---
layout : default
title : OrderPickRequest
parent : Tables
---
# OrderPickRequest

📊 **Overview:** 4 Fields | 3 Indexes | 2 Many-to-One Relations | 2 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 124
- **UUID:** 2BE22D1782098249A524034DE15E0047
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T23:19:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PickRequestID | `Date` | - | - |
| CustomerOrderID | `Date` | - | - |
| Quantity | `Date` | - | - |

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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T23:19:49Z*
