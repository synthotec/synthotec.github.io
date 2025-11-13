---
layout : default
title : Stock_Movement
parent : Tables
---
# Stock_Movement

📊 **Overview:** 24 Fields | 4 Indexes | 2 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 5
- **UUID:** F1AE2CED84FC204E9E788B8FF9BE9359
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:34:18Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (24)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (2)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Movement_Type_From_s | `String` (2) | 🚫 Not Null | - |
| Date_Of_Movement_d | `Integer` | 🚫 Not Null | - |
| Works_Order_No_l | `Date` | 🚫 Not Null | - |
| Quantity_In_l | `Date` | 🚫 Not Null | - |
| Advice_Note_No_i | `Date` | 🚫 Not Null | - |
| Quantity_Out_l | `Date` | 🚫 Not Null | - |
| Stock_Movement_b | `Real` | 🚫 Not Null | - |
| Cert_Of_Conformance_No_i | `Date` | 🚫 Not Null | - |
| From_Location_l | `Date` | 🚫 Not Null | - |
| UserName_txt | `String` | 🚫 Not Null | - |
| ProductID_l | `Date` | 🚫 Not Null | - |
| To_Location_l | `Date` | 🚫 Not Null | - |
| Reason_For_Movement_txt | `String` | 🚫 Not Null | - |
| Movement_Type_To_s | `String` (2) | 🚫 Not Null | - |
| StockMovementID_l | `Date` | 🚫 Not Null | - |
| DeliveryMethod_txt | `String` | 🚫 Not Null | - |
| Order_No_s | `String` (30) | 🚫 Not Null | - |
| FullPallet_l | `Date` | 🚫 Not Null | - |
| is_consigment_stock_b | `Real` | 🚫 Not Null | - |
| NSKFromBox | `Date` | 🚫 Not Null | - |
| NSKToBox | `Date` | 🚫 Not Null | - |
| TransactionID | `Date` | 🚫 Not Null | - |
| MoveListNum | `Date` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### Movement_Type_From_s

**Properties:**

- **Type:** String (max length: 2)
- **Constraints:** 🚫 Never Null

---

#### Date_Of_Movement_d

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### Works_Order_No_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Quantity_In_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Advice_Note_No_i

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Quantity_Out_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Stock_Movement_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Cert_Of_Conformance_No_i

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### From_Location_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### UserName_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### ProductID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### To_Location_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Reason_For_Movement_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Movement_Type_To_s

**Properties:**

- **Type:** String (max length: 2)
- **Constraints:** 🚫 Never Null

---

#### StockMovementID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DeliveryMethod_txt

**Properties:**

- **Type:** String
- **Constraints:** 🚫 Never Null

---

#### Order_No_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### FullPallet_l

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### is_consigment_stock_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### NSKFromBox

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### NSKToBox

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### TransactionID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### MoveListNum

**Properties:**

- **Type:** Date
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
| `ProductID_l` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Works_Order_No_l` | Keywords | regular | - |
| `Date_Of_Movement_d` | Keywords | regular | - |

### Detailed Information

- **Field:** `ProductID_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Works_Order_No_l`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Date_Of_Movement_d`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `Works_Order_No_l` → `Works_Order_No` | Active |
| `Stock_LocationEntity` | [Stock_Location](Stock_Location.md) | `To_Location_l` → `StockLocationID_l` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `Works_Order_No_l`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

#### Stock_LocationEntity

**Links to:** [Stock_Location](Stock_Location.md)

- **Source Field:** `To_Location_l`
- **Destination Field:** `StockLocationID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:34:18Z*
