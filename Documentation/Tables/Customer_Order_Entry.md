---
layout : default
title : Customer_Order_Entry
parent : Tables
---
# Customer_Order_Entry

📊 **Overview:** 8 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 16
- **UUID:** AF0EF9F5DE55394BA5A574DC03975466
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:04Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (8)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Order_ID | `String` (10) | 🚫 Not Null | - |
| Batch_No | `String` (3) | 🚫 Not Null | - |
| CustomerDeliveryDate | `Integer` | 🚫 Not Null | - |
| OurDeliveryDate | `Integer` | 🚫 Not Null | - |
| QuantityOrdered | `Date` | 🚫 Not Null | - |
| Nominal Sale | `Boolean` | 🚫 Not Null | - |
| Is_Replacement | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### Order_ID

**Properties:**

- **Type:** String (max length: 10)
- **Constraints:** 🚫 Never Null

---

#### Batch_No

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### CustomerDeliveryDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### OurDeliveryDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### QuantityOrdered

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Nominal Sale

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Is_Replacement

**Properties:**

- **Type:** Real
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
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:04Z*
