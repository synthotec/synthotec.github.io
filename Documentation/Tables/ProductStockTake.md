---
layout : default
title : ProductStockTake
parent : Tables
---
# ProductStockTake

📊 **Overview:** 7 Fields | 1 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 55
- **UUID:** CD7EC16B6973004E85CD5D29E07127D6
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:53Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (7)
- [🔍 Indexes](#-indexes) (1)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| WO | `Date` | 🚫 Not Null | - |
| ProductID | `Date` | 🚫 Not Null | - |
| PartsCounted | `Date` | 🚫 Not Null | - |
| BoxesCounted | `Picture` | 🚫 Not Null | - |
| ActualStock | `Date` | 🚫 Not Null | - |
| sDate | `Integer` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### WO

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### PartsCounted

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### BoxesCounted

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### ActualStock

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### sDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | B-Tree | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** B-Tree

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WO` → `Works_Order_No` | Active |
| `ProductEntity` | [Product](Product.md) | `ProductID` → `Product_ID` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WO`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID`
- **Destination Field:** `Product_ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:53Z*
