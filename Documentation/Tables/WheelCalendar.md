---
layout : default
title : WheelCalendar
parent : Tables
---
# WheelCalendar

📊 **Overview:** 24 Fields | 10 Indexes | 3 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 51
- **UUID:** DE47E38D9F06C94798575B35E1D1A5C3
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:49Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (24)
- [🔍 Indexes](#-indexes) (10)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (3)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Machine | `Picture` | 🚫 Not Null | - |
| MCDate | `Integer` | 🚫 Not Null | - |
| Hours | `Boolean` | 🚫 Not Null | - |
| RegrindAmountKg | `Boolean` | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| MatID | `Date` | 🚫 Not Null | - |
| MatAmountKG | `Boolean` | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| Parts | `Date` | 🚫 Not Null | - |
| ToolChange | `Real` | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| ToolNumber | `String` (255) | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| DateReq | `Integer` | 🚫 Not Null | - |
| TotalQty | `Date` | 🚫 Not Null | - |
| SetDate | `Integer` | 🚫 Not Null | - |
| WheelID | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| HasSetDate | `Real` | 🚫 Not Null | - |
| RemainingHours | `Boolean` | 🚫 Not Null | - |
| Trial | `Real` | 🚫 Not Null | - |
| ToolID | `Date` | 🚫 Not Null | - |
| ChangeDate | `Integer` | 🚫 Not Null | - |

### Detailed Information

#### Machine

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### MCDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Hours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### RegrindAmountKg

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MatID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MatAmountKG

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Pallet

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Mandrel

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Parts

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ToolChange

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### PartName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ToolNumber

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DateReq

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### TotalQty

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### SetDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### WheelID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### HasSetDate

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### RemainingHours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Trial

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ToolID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ChangeDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ProductID` | Keywords | regular | - |
| `MatID` | Keywords | regular | - |
| `WorksOrder` | Keywords | regular | - |
| `Machine` | Cluster | regular | - |
| `PartName` | Cluster | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `MCDate` | Keywords | regular | - |
| `ToolChange` | Cluster | regular | - |
| `WheelID` | Cluster | regular | - |
| `ToolID` | Cluster | regular | - |

### Detailed Information

- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MatID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Machine`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `PartName`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MCDate`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ToolChange`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `WheelID`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `ToolID`
  - **Kind:** regular
  - **Type:** Cluster

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `MaterialEntity` | [Material](Material.md) | `MatID` → `Unique_ID` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |

### Detailed Information

#### MaterialEntity

**Links to:** [Material](Material.md)

- **Source Field:** `MatID`
- **Destination Field:** `Unique_ID`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:49Z*
