---
layout : default
title : ProductReturn
parent : Tables
---
# ProductReturn

📊 **Overview:** 9 Fields | 3 Indexes | 1 Many-to-One Relations | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 30
- **UUID:** 84D5CEC865744441A28B55BDFF4F334A
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:21Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ReturnID_l | `Date` | 🚫 Not Null | - |
| DateOfReturn_d | `Integer` | 🚫 Not Null | - |
| ReturnNotes_txt | `String` | 🚫 Not Null | - |
| PQI_No_s | `String` (15) | 🚫 Not Null | - |
| CustomerOrderDetails_s | `String` (50) | 🚫 Not Null | - |
| ProductID_l | `Date` | 🚫 Not Null | - |
| CustomerCode_s | `String` (3) | 🚫 Not Null | - |
| ReturnClosed_b | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### ReturnID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DateOfReturn_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ReturnNotes_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### PQI_No_s

**Properties:**

- **Type:** String (max length: 15)
- **Constraints:** 🚫 Never Null

---

#### CustomerOrderDetails_s

**Properties:**

- **Type:** String (max length: 50)
- **Constraints:** 🚫 Never Null

---

#### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### CustomerCode_s

**Properties:**

- **Type:** String (max length: 3)
- **Constraints:** 🚫 Never Null

---

#### ReturnClosed_b

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
| `ID` | B-Tree | regular | ✨ Yes |
| `ProductID_l` | Keywords | regular | - |
| `ReturnID_l` | Keywords | regular | - |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** B-Tree
- **Field:** `ProductID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ReturnID_l`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `ProductEntity` | [Product](Product.md) | `ProductID_l` → `Product_ID` | Active |

### Detailed Information

#### ProductEntity

**Links to:** [Product](Product.md)

- **Source Field:** `ProductID_l`
- **Destination Field:** `Product_ID`
- **State:** Active

---

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ProductReturnWorksOrderSelection` | [ProductReturnWorksOrder](ProductReturnWorksOrder.md) | `ReturnID_l` → `ReturnID_l` | Active |

### Detailed Information

#### ProductReturnWorksOrderSelection

**Links from:** [ProductReturnWorksOrder](ProductReturnWorksOrder.md)

- **Source Table:** `ProductReturnWorksOrder`
- **Source Field:** `ReturnID_l`
- **This Table Field:** `ReturnID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:21Z*
