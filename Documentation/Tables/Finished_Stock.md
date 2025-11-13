---
layout : default
title : Finished_Stock
parent : Tables
---
# Finished_Stock

📊 **Overview:** 12 Fields | 6 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 12
- **UUID:** 51AABC1ABE247B49864812D98CE6E30B
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:00Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (12)
- [🔍 Indexes](#-indexes) (6)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| FinishedStockID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| ProductID_l | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Reuse_Issue_No | `String` (5) | 🚫 Not Null | - |
| MaterialID | `Picture` | 🚫 Not Null | - |
| Stock_Quantity | `Date` | 🚫 Not Null | - |
| Reuse_NoOfBoxes | `Date` | 🚫 Not Null | - |
| Reuse_PartBoxQty | `Date` | 🚫 Not Null | - |
| Reuse_WIP | `Date` | 🚫 Not Null | - |
| LocationID_l | `Date` | 🚫 Not Null | - |
| Works_Order_No | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Pallet_ID | `Date` | 🚫 Not Null | - |

### Detailed Information

#### FinishedStockID

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Reuse_Issue_No

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### MaterialID

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Stock_Quantity

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Reuse_NoOfBoxes

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Reuse_PartBoxQty

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Reuse_WIP

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### LocationID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Works_Order_No

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### Pallet_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |
| `LocationID_l` | Keywords | regular | - |
| `ProductID_l` | Keywords | regular | - |
| `Works_Order_No` | Keywords | regular | - |
| `FinishedStockID` | Keywords | regular | - |
| `MaterialID` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `LocationID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ProductID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Works_Order_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `FinishedStockID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `MaterialID`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No` → `Works_Order_No` | Active |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `LocationID_l` → `StockLocationID_l` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `LocationID_l`
- **Destination Field:** `StockLocationID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:00Z*
