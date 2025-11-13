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
- **Generated:** 🕐 2025-11-13T02:36:55Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| PickRequestID | `Date` | - | - |
| CustomerOrderID | `Date` | - | - |
| Quantity | `Date` | - | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### PickRequestID

**Properties:**

- **Type:** Date

---

#### CustomerOrderID

**Properties:**

- **Type:** Date

---

#### Quantity

**Properties:**

- **Type:** Date

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `CustomerOrderID` | Keywords | regular | - |
| `PickRequestID` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `CustomerOrderID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `PickRequestID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `PickRequestEntity` | [PickRequest](PickRequest.md) | `PickRequestID` → `ID` | Active |
| `Customer_OrderEntity` | [Customer_Order](Customer_Order.md) | `CustomerOrderID` → `Petes_No` | Active |

### Detailed Information

#### PickRequestEntity

**Links to:** [PickRequest](PickRequest.md)

- **Source Field:** `PickRequestID`
- **Destination Field:** `ID`
- **State:** Active

---

#### Customer_OrderEntity

**Links to:** [Customer_Order](Customer_Order.md)

- **Source Field:** `CustomerOrderID`
- **Destination Field:** `Petes_No`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `PalletSelection` | [Pallet](Pallet.md) | `OrderPickRequestID` → `ID` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `OrderPickRequestID` → `ID` | Active |

### Detailed Information

#### PalletSelection

**Links from:** [Pallet](Pallet.md)

- **Source Table:** `Pallet`
- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `OrderPickRequestID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:55Z*
