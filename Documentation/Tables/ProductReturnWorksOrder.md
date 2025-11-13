---
layout : default
title : ProductReturnWorksOrder
parent : Tables
---
# ProductReturnWorksOrder

📊 **Overview:** 8 Fields | 3 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 31
- **UUID:** 130945D5E0DF0E4498FBB20449311F51
- **Primary Key:** 🔑 `WOReturnID_l`
- **Generated:** 🕐 2025-11-13T02:35:22Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **WOReturnID_l** | `Date` | 🔑 PK, ✨ Unique, 🚫 Not Null | - |
| ReturnID_l | `Date` | 🚫 Not Null | - |
| Works_Order_No_l | `Date` | 🚫 Not Null | - |
| ReturnedQuantity_l | `Date` | 🚫 Not Null | - |
| Scrapped_b | `Real` | 🚫 Not Null | - |
| Restocked_b | `Real` | 🚫 Not Null | - |
| ScrappedQuantity_l | `Date` | 🚫 Not Null | - |
| RestockedQuantity_l | `Date` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 WOReturnID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, 🚫 Never Null

---

#### ReturnID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Works_Order_No_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ReturnedQuantity_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Scrapped_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Restocked_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### ScrappedQuantity_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### RestockedQuantity_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ReturnID_l` | Keywords | regular | - |
| `WOReturnID_l` | Keywords | regular | ✨ Yes |
| `Works_Order_No_l` | Keywords | regular | - |

### Detailed Information

- **Field:** `ReturnID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WOReturnID_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Works_Order_No_l`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductReturnEntity` | [ProductReturn](ProductReturn.md) | `ReturnID_l` → `ReturnID_l` | Active |
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No_l` → `Works_Order_No` | Active |

### Detailed Information

#### ProductReturnEntity

**Links to:** [ProductReturn](ProductReturn.md)

- **Source Field:** `ReturnID_l`
- **Destination Field:** `ReturnID_l`
- **State:** Active

---

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No_l`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:22Z*
