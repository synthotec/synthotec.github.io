---
layout : default
title : Stock_Location
parent : Tables
---
# Stock_Location

📊 **Overview:** 6 Fields | 4 Indexes | 5 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 29
- **UUID:** 916903B13AB83B4A9937B1348364CCA9
- **Primary Key:** 🔑 `StockLocationID_l`
- **Generated:** 🕐 2025-11-13T02:35:20Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (4)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (5)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **StockLocationID_l** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |
| Location_Name_s | `String` (30) | 🚫 Not Null | - |
| Is_Consignment_b | `Real` | 🚫 Not Null | - |
| Location_Code_s | `String` (5) | 🚫 Not Null | - |
| DeafultPackingLocation_b | `Real` | 🚫 Not Null | - |
| DespatchLocation | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 StockLocationID_l

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

#### Location_Name_s

**Properties:**

- **Type:** String (max length: 30)
- **Constraints:** 🚫 Never Null

---

#### Is_Consignment_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Location_Code_s

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### DeafultPackingLocation_b

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DespatchLocation

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `Is_Consignment_b` | Keywords | regular | - |
| `DeafultPackingLocation_b` | Keywords | regular | - |
| `DespatchLocation` | Keywords | regular | - |
| `StockLocationID_l` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `Is_Consignment_b`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `DeafultPackingLocation_b`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `DespatchLocation`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `StockLocationID_l` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `Stock_MovementSelection` | [Stock_Movement](Stock_Movement.md) | `To_Location_l` → `StockLocationID_l` | Active |
| `Finished_StockSelection` | [Finished_Stock](Finished_Stock.md) | `LocationID_l` → `StockLocationID_l` | Active |
| `CofCSelection` | [CofC](CofC.md) | `LocationID_l` → `StockLocationID_l` | Active |
| `BoxLabelsSelection` | [BoxLabels](BoxLabels.md) | `Stock_LocationID` → `StockLocationID_l` | Active |
| `CustomerSelection` | [Customer](Customer.md) | `ConsignmentLocationID` → `StockLocationID_l` | Active |

### Detailed Information

#### Stock_MovementSelection

**Links from:** [Stock_Movement](Stock_Movement.md)

- **Source Table:** `Stock_Movement`
- **Source Field:** `To_Location_l`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

#### Finished_StockSelection

**Links from:** [Finished_Stock](Finished_Stock.md)

- **Source Table:** `Finished_Stock`
- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

#### CofCSelection

**Links from:** [CofC](CofC.md)

- **Source Table:** `CofC`
- **Source Field:** `LocationID_l`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

#### BoxLabelsSelection

**Links from:** [BoxLabels](BoxLabels.md)

- **Source Table:** `BoxLabels`
- **Source Field:** `Stock_LocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

#### CustomerSelection

**Links from:** [Customer](Customer.md)

- **Source Table:** `Customer`
- **Source Field:** `ConsignmentLocationID`
- **This Table Field:** `StockLocationID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:20Z*
